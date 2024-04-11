
# git: https://github.com/strasdat/Sophus.git
# commit: d270df2be6e46501b1e7efc09b107517e0be0645

cc_library(
  NAME
    sophus
  HDRS
    "common.hpp"
    "rotation_matrix.hpp"
    "se2.hpp"
    "se3.hpp"
    "so2.hpp"
    "so3.hpp"
    "types.hpp"
  DEPS
    Eigen3::Eigen
  INTERFACE)
