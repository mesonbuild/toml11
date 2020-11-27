project('toml11',
    'cpp',
    version : '3.6.0',
    license : 'MIT'
)

install_headers('toml.hpp')
install_headers('toml/color.hpp', subdir: 'toml')
install_headers('toml/combinator.hpp', subdir: 'toml')
install_headers('toml/comments.hpp', subdir: 'toml')
install_headers('toml/datetime.hpp', subdir: 'toml')
install_headers('toml/exception.hpp', subdir: 'toml')
install_headers('toml/from.hpp', subdir: 'toml')
install_headers('toml/get.hpp', subdir: 'toml')
install_headers('toml/into.hpp', subdir: 'toml')
install_headers('toml/lexer.hpp', subdir: 'toml')
install_headers('toml/literal.hpp', subdir: 'toml')
install_headers('toml/parser.hpp', subdir: 'toml')
install_headers('toml/region.hpp', subdir: 'toml')
install_headers('toml/result.hpp', subdir: 'toml')
install_headers('toml/serializer.hpp', subdir: 'toml')
install_headers('toml/source_location.hpp', subdir: 'toml')
install_headers('toml/storage.hpp', subdir: 'toml')
install_headers('toml/string.hpp', subdir: 'toml')
install_headers('toml/traits.hpp', subdir: 'toml')
install_headers('toml/types.hpp', subdir: 'toml')
install_headers('toml/utility.hpp', subdir: 'toml')
install_headers('toml/value.hpp', subdir: 'toml')

pkgc = import('pkgconfig')
pkgc.generate(name: 'toml11',
    version: meson.project_version(),
    description: 'TOML for Modern C++'
)

toml11_dep = declare_dependency(
    include_directories : include_directories('.')
)
