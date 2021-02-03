## IP Checklist for Functional RTL Freeze
An item is "signed off" once the `Signed-off By` and `Sign-off Date` cells are filled in. `Signed-off By` should be an email address.  If there is an Exception or Waiver, it should be captured as a GitHub issue in core-v-docs and the issue number recorded in the `Exceptions/Waiver/Comment` cell.


| Category         | Item                                              | Sign-off Criteria                                                                                                                                                                                                                                                                                                                                                                                                                   | Signed-off By                 | Sign-off Date  | Exceptions/Waivers/Comments                                                                                                                                                                                                      |
| ---------------- | ------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------- | ---------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| IP Review      | IP review on core-v-cv32e40p design repo         | Eclipse “CQ” audit complete                                                                                                                                                                                                                                                                                                                                                                                                         | duncan@openhwgroup.org   | 2020-12-17 | https://dev.eclipse.org/ipzilla/show_bug.cgi?id=22444                                                                                                                                                                                       |
| IP Review      | IP review on core-v-verif verification repo      | Eclipse “CQ” audit complete                                                                                                                                                                                                                                                                                                                                                                                                         | duncan@openhwgroup.org   | 2020-12-17 | https://dev.eclipse.org/ipzilla/show_bug.cgi?id=22415                                                                                                                                                                                       |
| IP Review      | IP audit on core-v-docs user documentation only | OpenHW Staff audit complete                                                                                                                                                                                                                                                                                                                                                                                                        | duncan@openhwgroup.org   | 2020-12-17  |     [cv32e40p user manual](https://github.com/openhwgroup/core-v-docs/tree/master/cores/cv32e40p/user_manual/source) and [verification strategy](https://github.com/openhwgroup/core-v-docs/tree/master/verif/Common/CORE-V_Verification_Strategy/source) files have appropriate headers                                                                                                                                                                                   |