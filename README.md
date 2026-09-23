# MiniTorch Module 0

<img src="https://minitorch.github.io/minitorch.svg" width="50%">

* Docs: https://minitorch.github.io/

* Overview: https://minitorch.github.io/module0/module0/

## Test Results

```
$ python3 -m pytest tests/ -v
...
tests/test_module.py::test_stacked_demo PASSED
tests/test_module.py::test_module PASSED
tests/test_module.py::test_stacked_module PASSED
tests/test_module.py::test_module_fail_forward XFAIL
tests/test_module.py::test_module_forward PASSED
tests/test_module.py::test_parameter PASSED
tests/test_operators.py::test_same_as_python PASSED
tests/test_operators.py::test_relu PASSED
tests/test_operators.py::test_relu_back PASSED
tests/test_operators.py::test_id PASSED
tests/test_operators.py::test_lt PASSED
tests/test_operators.py::test_max PASSED
tests/test_operators.py::test_eq PASSED
tests/test_operators.py::test_sigmoid PASSED
tests/test_operators.py::test_transitive PASSED
tests/test_operators.py::test_symmetric PASSED
tests/test_operators.py::test_distribute PASSED
tests/test_operators.py::test_other PASSED
tests/test_operators.py::test_zip_with PASSED
tests/test_operators.py::test_sum_distribute PASSED
tests/test_operators.py::test_sum PASSED
tests/test_operators.py::test_prod PASSED
tests/test_operators.py::test_negList PASSED
tests/test_operators.py::test_one_args[fn0..fn13] PASSED
tests/test_operators.py::test_two_args[fn0..fn5] PASSED
tests/test_operators.py::test_backs PASSED

======================== 43 passed, 1 xfailed in 1.85s ========================
```
