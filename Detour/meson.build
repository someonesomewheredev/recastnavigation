detour_srcs = [
    'Source/DetourAlloc.cpp',
    'Source/DetourAssert.cpp',
    'Source/DetourCommon.cpp',
    'Source/DetourNavMesh.cpp',
    'Source/DetourNavMeshBuilder.cpp',
    'Source/DetourNavMeshQuery.cpp',
    'Source/DetourNode.cpp'
]

detour_inc = include_directories('Include')

detour = static_library(
    'detour',
    sources: detour_srcs,
    include_directories: detour_inc,
)

detour_dep = declare_dependency(link_with : [detour], include_directories: detour_inc)