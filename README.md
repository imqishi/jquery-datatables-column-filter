# jquery-datatables-column-filter
Add some features and automatically exported from code.google.com/p/jquery-datatables-column-filter

# Features Added:

1. Set search area width:100% to solve table not compact problem.
2. Change search action trigger from enter to blur so that will not have so many requests.
3. Add range selector dependency, you can directly use range filter now.
4. Add type 'hidden' to create a hidden input for extended use. For example, in many tables there's a column named 'handle' without filter. If we want to send some other params via dataTables we can set that column a hidden input and manually set outer inputs' value to this one and trigger a blur event. Your data will be sent by sSearch_xxx.
