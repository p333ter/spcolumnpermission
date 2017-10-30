# This Solution is only for SharePoint 2010!

Features:
Column Permission
- Hide or Read Only Columns in a List Forms (New/Edit/Display)
- Hide Columns in Views
- Hide Columns in DataSheet Views
- Hide Columns in Alert Me Emails
- Specify the permission for Users, SharePoint Groups or Active Directory Groups

View Permission
- Disable Views
- Hide Views in Context Menus
- Automatically Disable Views in Custom WebPart Zones
- Specify the permission for Users, SharePoint Groups or Active Directory Groups

### Column Permission:
1. After successful Installation and Activation on Site Collection you will see two new links in your List/Document Library Settings page.

2. Click on Column Permission and on New Page you will see all columns created by user for specific list.

3. In Modal Dialog you are able to specify the permission for Users, SharePoint Groups or Active Directory Groups. If you specify in last section hidden permission these users will not have permission to view columns also in Views and Alert Me Emails. 

4. So In New Form You will not see Hidden Column Number.

5. In Edit Form Column Number will be Read Only.

6. In Views Column Number will be Hidden.

7. In Alert Email the Column Number will be Hidden also.

8. Column Number will be Hidden also in DataSheet View

So you can combine permission for New/Edit/Display forms for all columns created by userwithout any problem. If you choose to Hide column for Display form the column will also be not visible in Views and Alerts.


### View Permission:
1. After successful Installation and Activation on Site Collection you will see two new links in your List/Document Library Settings page.

2. Click on View Permission and on New Page you will see all Views created by user for specific list.
3. Now specify the permission for Users, SharePoint Groups or Active Directory Groups which will not have the permission to get to these Views.

4. Users which don't have the permission will not even see these views in context menu and also if they type correct URL to these Views they will be redirected to Access Denied Page.

If user doesn't have permission for View and View is used on some Webpart Page Zone the View will be also disabled on this page. 

If this checkbox is checked you need to specify the permission for users or groups like in SharePoint.

I think that solution is simple and for me, it works without any problem. As I said this solution is not perfect and never will be but I am still working on it. With combination of Column and View permission you can get very nice results.
