# Isostasy tests

This folder has a selection of tests to evaluate how UW deal with an isostatic boundary condition.

All tests are setup to be relatively simple, so that their results can be compared to analytical calculations.

All notebooks have a quick hypothesis at the beginning, and a quick summary at the end.

In summary:

- Isostasy 1: A simple layered model to test the pressure boundary condition gives an expected result.
- Isostasy 2: A slightly more complex model that allows the model to neck in the centre.
- Isostasy 3: Sedimentation is added to the Isostasy 1 model to see the impact it has.
- Isostasy 4: A different set of boundary conditions are applied to the Isostasy 1 model to see how it compares.
- Isostasy 5: Sedimentation is added to the Isostasy 2 model.
- Isostasy 6: The same as Isostasy 5, but using the LecodeIsostasy boundary condition, which reveals a bug in that implementation.
