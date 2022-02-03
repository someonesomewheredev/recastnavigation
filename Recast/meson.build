recast_srcs = [
    'Source/Recast.cpp',
    'Source/RecastAlloc.cpp',
    'Source/RecastArea.cpp',
    'Source/RecastAssert.cpp',
    'Source/RecastContour.cpp',
    'Source/RecastFilter.cpp',
    'Source/RecastLayers.cpp',
    'Source/RecastMesh.cpp',
    'Source/RecastMeshDetail.cpp',
    'Source/RecastRasterization.cpp',
    'Source/RecastRegion.cpp'
]

recast_inc = include_directories('Include')

recast = static_library(
    'recast',
    sources: recast_srcs,
    include_directories: recast_inc,
)

recast_dep = declare_dependency(link_with : [recast], include_directories: recast_inc)