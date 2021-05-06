## :sparkles: PI-works UI Specification Document :sparkles:

![UI-userManagement](https://user-images.githubusercontent.com/57603284/117329092-f694a500-ae9c-11eb-90e9-ea29320176d0.png)


1. At **start/begining** only section A and B is displayed.
- [x] ***Save User***: the save user button is disabled/hidden by default.

2. ### Section A.
- [x] ***+New User***: when this button is pressed, displayes section C and the **Save User** button is diaplyed.
- [x] ***Hide Disbled User***: when checked, hides all the users with **Enabled** property set to **true** in the table on Section B.
- [x] ***Save User***: when pressed, the information entered in the form is validated, if correct it is saved and displayed in the table on Section B, otherwise validation erros are displayed back on the form on Section C and the state remains unchanged.

3. ### Section B.
- [x] when table headings **[ID, User Name, Email, Enabled]** are pressed, data in the table should be ordered (^ascending or descrending) by the selected heading.
- [x] when the filter icons in the table header is pressed, the filter options specific to that column should be displyed i.e. **Enabled** column can be filtered by **true** or **false** options. 

4. ### Section C.
- [x] All input fields except ***Display Name*** are **Required**.
- [ ] The default status of a newly created user is Disbled.
- [x] if ***Display Name*** is not required, ***Username*** is is automatilcally used on submission.
- [x] the error messages should be displayed below every required input fileds.
- [x] ***User Roles***: when pressed, the drop doen menu is displayed showing roles options **[Guest, Admin, Super Admin]**.
