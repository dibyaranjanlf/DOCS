# Authorize Contributors

You can authorize contributors by adding their name to the Aprroved List. **Approved Lists** are lists of domain names, email addresses of individuals, GitHub usernames, or GitHub organization names who are authorized to contribute under a signed Corporate CLA. As a CCLA manager, you allow contributions to projects on behalf of your company by using any approved list:

* Domain Approved List allows entities to contribute under any email address under that domain name.
* Email Approved List allows entities to contribute under an individual email address.
* GitHub Approved List allows entities to contribute under a GitHub username.
* GitHub Organization Approved List allows entities to contribute under a GitHub organization name.

Each approved list applies to the project for which the company has signed a Corporate CLA. The CLA application checks all the approved lists for allowing contributions to a company project. A contributor only needs to be on one approved list. Contributors can use EasyCLA to send email requests to be associated \(authorized\) with the company.

_Multiple CCLA managers cannot authorize/approve the same domain and sign a CCLA for the same company._

**Do these steps:**

1. ​[Sign in](sign-in-to-the-cla-corporate-console.md).

2. The CLA Corporate Console appears and shows Companies.

3. Click a **company** of interest.

4. The CLA Corporate Console appears and shows Signed CLAs.

![Signed CLAs](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LuWIT3NfRhMt-F50U5n%2F-LuXUenJzl7sWiTp19eT%2F-LuXUgxp2Gfw1K9xp_jp%2Fcla-signed-clas.png?generation=1574684254209917&alt=media)

5. Click a **CLA**.

The approved lists appear:

![Whitelists](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LuWIT3NfRhMt-F50U5n%2F-LuXUenJzl7sWiTp19eT%2F-LuXUgxrxZtNfekGaZ8b%2Fcla-whitelists.png?generation=1574684254580013&alt=media)

6. Decide which approved list you want to edit:

* [Domain Approved List , Email Approved List, or GitHub Approved List](whitelist-contributors.md#domain-whitelist-email-whitelist-or-github-whitelist)
* [GitHub Organization Approved List](whitelist-contributors.md#github-organization-whitelist)

## Domain Approved List , Email Approved List, or GitHub Approved List <a id="domain-whitelist-email-whitelist-or-github-whitelist"></a>

The corresponding Edit _domain/email/github_ approved list dialog lets you add, edit, and delete values to the approved list so that employees \(developers\) can be associated to the company. An example domain name value is joesbikes.com. A wildcard approves/authorizes the domain and all subdomains, for example: \*.joesbikes.com or \*joesbikes.com would authorize joes.bikes.com, shop.joesbikes.com, and blog.joesbikes.com.

**Note:** To remove an entry from the approved list, click **X** next to the item, and click **SAVE**.

1. Click the edit icon\( **pencil** \) next to the approved list that you want to edit:
2. Click **ADD DOMAIN/EMAIL/GITHUB**, enter a **domain name**, **email address**, or **GitHub username** for the employees for whom you want to authorize, respectively, and click **SAVE**. For example:

![Edit email Whitelist](https://gblobscdn.gitbook.com/assets%2F-LuWIT3NfRhMt-F50U5n%2F-LuXUenJzl7sWiTp19eT%2F-LuXUgxvL5WG4fjyScmx%2Fcla-edit-email-whitelist.png?generation=1574684260759456&alt=media)

Your entries appear in their corresponding approved lists.

## GitHub Organization Approved List <a id="github-organization-whitelist"></a>

The GitHub Organization Approved List lets you add or remove organizations from an approved list so that company employees can contribute to project—the CLA service checks the GitHub organizations that the user belongs to.

_**Requirements:**_

Each member of your organization must ensure that these items are Public in their GitHub Profile:

* Their membership with the organization. Each Private member should follow this [procedure](https://help.github.com/en/articles/publicizing-or-hiding-organization-membership) to make their membership Public.
* The associated email address for the organization member. Each Private member should make their associated email address Public \(members can have multiple emails in their Profile, so they must select the appropriate one\).

**Do these steps:**

1. Click the edit icon \(**pencil\)** next to Github Org Approved List.  
    The Github Organization Approved List dialog appears.

![Github Organization Whitelist](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LuWIT3NfRhMt-F50U5n%2F-LuXUenJzl7sWiTp19eT%2F-LuXUgxxP0dhfxV5XHc-%2Fcla-github-organization-whitelist-no-organizations.png?generation=1574684254778432&alt=media)

**Note:** Click **CONNECT GITHUB** if the organization you want to authorize is not listed in the dialog. The Add GitHub Organization dialog appears and lets you specify the GitHub organization.

2. Click **ADD** or **REMOVE** next to the organization that you want to add or remove, respectively.

Your organizations appear in their organization approved list.
