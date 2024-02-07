### Version 0.2.0

#### New features

* [feat(modflowapi)](https://github.com/MODFLOW-USGS/modflowapi/commit/3cc77dad6eae6c0fdb8ea856bc3ea3e7285ca658): Base files for modflowapi package. Committed by Joseph D Hughes on 2021-05-11.

#### Bug fixes

* [fix(get value)](https://github.com/MODFLOW-USGS/modflowapi/commit/defd2ee2bfc840ee2b7b3df76fcea4af651f1936): Fixed error handling when modflowapi fails to get a pointer to a value from the API (#9). Committed by spaulins-usgs on 2023-02-24.

#### Refactoring

* [refactor(rhs, hcof, AdvancedInput)](https://github.com/MODFLOW-USGS/modflowapi/commit/2c4d893eaa96457be099313a220c7c7d8fca888a): Bug fixes for setting variable values for advanced inputs. Committed by Joshua Larsen on 2023-02-25.
* [refactor(EOL)](https://github.com/MODFLOW-USGS/modflowapi/commit/e0ca9e80a60ae6c85933a69ec322a5bc861a32ab): Change CRLF to LF line endings for source files (#12). Committed by Mike Taves on 2023-03-24.
* [refactor(test_rhs_hcof_advanced)](https://github.com/MODFLOW-USGS/modflowapi/commit/a8e241df1def5899ccbf22368eddc76da0d7a60c): Add additional test  (#13). Committed by Joshua Larsen on 2023-03-29.
* [refactor(rhs, hcof)](https://github.com/MODFLOW-USGS/modflowapi/commit/c0f681c5b7525388ead4df8c6363c1b4514d6de6): Updates to allow setting values when rhs and hcof have not yet had pointers set.. Committed by Joshua Larsen on 2023-04-28.
* [refactor(Quickstart.ipynb)](https://github.com/MODFLOW-USGS/modflowapi/commit/3b6675aa687f5af01813abfdb143c7ddd4343646): Fix error in callback_function. Committed by Joshua Larsen on 2023-07-17.
* [refactor(rhs, hcof)](https://github.com/MODFLOW-USGS/modflowapi/commit/ce4e50286d66da51c6b05f0de29c7c646344f6ce): Allow setting rhs and hcof when pointers have not been previously set. Committed by Joshua Larsen on 2023-07-17.
* [refactor](https://github.com/MODFLOW-USGS/modflowapi/commit/e693282611d5863bafeece362230a4aadd02311f): Update libmf6 path handling (#27). Committed by w-bonelli on 2023-08-03.
* [refactor(_ptr_to_recarray)](https://github.com/MODFLOW-USGS/modflowapi/commit/5a631592f2da57bf1564c263e9602c46e5a5a50c): Slice pointers prior to setting data to recarray. Committed by Joshua Larsen on 2023-08-08.
* [refactor(_ptr_to_recarray)](https://github.com/MODFLOW-USGS/modflowapi/commit/959fe31abda263a52d01262af7dc4c2a878eadb5): Slice pointers prior to setting data to recarray. Committed by Joshua Larsen on 2023-08-08.
* [refactor(extensions)](https://github.com/MODFLOW-USGS/modflowapi/commit/c97339d06e7386055e486f6354825ec15cea4638): Add support for IDM changes. Committed by Joshua Larsen on 2023-12-21.
* [refactor(extensions)](https://github.com/MODFLOW-USGS/modflowapi/commit/de0aff9c21d5d925235f306fd2b3d148c3281efa): Add support for IDM changes. Committed by Joshua Larsen on 2023-12-21.

