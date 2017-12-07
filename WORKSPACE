workspace(name = "skia")

new_http_archive(
    name = "jpeg",
    urls = [
        "https://mirror.bazel.build/github.com/libjpeg-turbo/libjpeg-turbo/archive/1.5.1.tar.gz",
        "https://github.com/libjpeg-turbo/libjpeg-turbo/archive/1.5.1.tar.gz",
    ],
    sha256 = "c15a9607892113946379ccea3ca8b85018301b200754f209453ab21674268e77",
    strip_prefix = "libjpeg-turbo-1.5.1",
    build_file = "BUILD.libjpeg",
)

new_http_archive(
    name = "freetype",
    urls = [
        "https://download.savannah.gnu.org/releases/freetype/freetype-2.8.1.tar.bz2",
    ],
    strip_prefix = "freetype-2.8.1",
    build_file = "BUILD.freetype",
)

new_git_repository(
    name = "fontconfig",
    remote = "https://anongit.freedesktop.org/git/fontconfig",
    tag = "2.12.6",
    build_file = "BUILD.fontconfig"
)

new_git_repository(
    name = "sfntly",
    remote = "https://github.com/rillig/sfntly",
    commit = "71b36ba9b512ddae85be6f9a3f6a3e808ae3ba82",
    build_file = "BUILD.sfntly",
)

#git_repository(
#    name = "com_github_spinorx_icu",
#    remote = "https://github.com/spinorx/icu.git",
#    tag = "v59.1.use"
#)

new_http_archive(
    name = "icu",
    urls = [
        "http://download.icu-project.org/files/icu4c/60.1/icu4c-60_1-src.tgz"
    ],
    strip_prefix = "icu",
    build_file = "BUILD.icu",
)

new_http_archive(
    name = "libpng",
    urls = [
        "https://mirror.bazel.build/github.com/glennrp/libpng/archive/v1.2.53.tar.gz",
        "https://github.com/glennrp/libpng/archive/v1.2.53.tar.gz",
    ],
    sha256 = "716c59c7dfc808a4c368f8ada526932be72b2fcea11dd85dc9d88b1df1dfe9c2",
    strip_prefix = "libpng-1.2.53",
    build_file = "BUILD.libpng",
)

new_http_archive(
    name = "com_github_madler_zlib",
    build_file = "BUILD.zlib",
    strip_prefix = "zlib-cacf7f1d4e3d44d871b605da3b647f07d718623f",
    url = "https://github.com/madler/zlib/archive/cacf7f1d4e3d44d871b605da3b647f07d718623f.tar.gz",
)

new_git_repository(
    name = "webp",
    remote = "https://chromium.googlesource.com/webm/libwebp.git",
    tag = "v0.6.1",
    build_file = "BUILD.libwebp",
)
