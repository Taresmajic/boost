project('boost', ['cpp'], version: '1.77.0')


r = run_command('git', 'submodule', 'update', '--init', check: true)


multiprecision_inc = include_directories('libs/multiprecision/include')
config_inc = include_directories('libs/config/include')
core_inc = include_directories('libs/core/include')
math_inc = include_directories('libs/math/include')
lexical_cast_inc = include_directories('libs/lexical_cast/include')
range_inc = include_directories('libs/range/include')
assert_inc = include_directories('libs/assert/include')
iterator_traits_inc = include_directories('libs/iterator/include')
mpl_inc = include_directories('libs/mpl/include')
preprocessor_inc = include_directories('libs/preprocessor/include')
type_traits_inc = include_directories('libs/type_traits/include')
static_assert_inc = include_directories('libs/static_assert/include')
detail_inc = include_directories('libs/detail/include')
concept_check_inc = include_directories('libs/concept_check/include')
utility_inc = include_directories('libs/utility/include')
throw_exception = include_directories('libs/throw_exception/include')
numeric_conversion_inc = include_directories('libs/numeric/conversion/include')
integer_traits_inc = include_directories('libs/integer/include')
array_inc = include_directories('libs/array/include')
container_inc = include_directories('libs/container/include')
move_inc = include_directories('libs/move/include')
rational_inc = include_directories('libs/rational/include')
predef_inc = include_directories('libs/predef/include')

multiprecision_dep = declare_dependency(
  include_directories: [
    multiprecision_inc,
    config_inc,
    core_inc,
    math_inc,
    lexical_cast_inc,
    range_inc,
    assert_inc,
    iterator_traits_inc,
    mpl_inc,
    preprocessor_inc,
    type_traits_inc,
    static_assert_inc,
    detail_inc,
    concept_check_inc,
    utility_inc,
    throw_exception,
    numeric_conversion_inc,
    integer_traits_inc,
    array_inc,
    container_inc,
    move_inc,
    rational_inc,
    predef_inc
    ])


