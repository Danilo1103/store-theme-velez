# Vélez


[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)]


Vélez Store Theme is basic store front model based on the VTEX IO Store Framework.


## Home
![image Home One](https://user-images.githubusercontent.com/94373834/219786632-320532d0-df1b-4bad-9334-f053147cefdf.png)
![image Home Two](https://user-images.githubusercontent.com/94373834/219796138-15fc4ff3-7add-4aa3-8a04-74728ae17b9c.png)

## Search Result
![image](https://user-images.githubusercontent.com/94373834/220421262-0cf12d38-e940-490b-9b80-a0d2708c3fb3.png)
![image](https://user-images.githubusercontent.com/94373834/220421537-3c20cc7e-9836-4dd2-b2bc-faa99962bd14.png)

## Detail Product
![image](https://user-images.githubusercontent.com/94373834/220422940-4cfba806-2a91-447a-93d5-fcfe0c3453d8.png)


### Step 1 -  Basic setup

Access the VTEX IO basic setup guide and follow all the given steps.
By the end of the setup, you should have the VTEX command line interface (Toolbelt) installed along with a developer workspace you can work in.



### Step 2 - Cloning the Velez Store Theme repository

[Clone this template](https://github.com/Danilo1103/store-theme-velez.git) repository to your local files to be able to effectively start working on it.
Then, access the repository's directory using your terminal.



### Step 3 - Editing the Manifest.json
Once in the repository directory, it is time to edit the Minimum Boilerplate manifest.json file.
Once you are in the file, you must replace the vendor and account values. vendor is the account name you are working on and account is anything you want to name your theme. For example:
json

```json
{
  "vendor": "store",
  "name": "store-theme",
}
```



### Step 4 - Installing required apps
In order to use Store Framework and work on your store theme, it is needed to have both vtex.store-sitemap and vtex.store installed.
Run  vtex list  and check whether those apps are already installed.
If they aren't, run the following command to install them:
```sh
vtex install vtex.store-sitemap vtex.store -f
```



### Step 5 - Uninstalling any existing theme
By running vtex list,  you can verify if any theme is installed.
It is common to already have a vtex.store-theme  installed when you start the store's front development process.
Therefore, if you find it in the app's list, copy its name and use it together with the command vtex uninstall. For example:

```sh
vtex uninstall vtex.store-theme
```

### Step 6- Run and preview your store
Then time has come to upload all the changes you made in your local files to the platform. For that, use the vtex link command.
If the process runs without any errors, the following message will be displayed: App linked successfully. Then, run the vtex browse command to open a browser window having your linked store in it.
This will enable you to see the applied changes in real time, through the account and workspace in which you are working.


## Dependencies
All store components that you see on this document are open source too. Production ready, you can found those apps in this GitHub organization.
Store framework is the baseline to create any store using VTEX IO Web Framework.

```json
{
  "dependencies": {
    "vtex.store": "2.x",
    "vtex.product-summary": "2.x",
    "vtex.slider": "0.x",
    "vtex.carousel": "2.x",
    "vtex.shelf": "1.x",
    "vtex.menu": "2.x",
    "vtex.minicart": "2.x",
    "vtex.product-details": "1.x",
    "vtex.product-kit": "1.x",
    "vtex.search-result": "3.x",
    "vtex.login": "2.x",
    "vtex.my-account": "1.x",
    "vtex.flex-layout": "0.x",
    "vtex.rich-text": "0.x",
    "vtex.locale-switcher": "0.x",
    "vtex.product-quantity": "1.x",
    "vtex.product-identifier": "0.x",
    "vtex.product-specification-badges": "0.x",
    "vtex.product-review-interfaces": "1.x",
    "vtex.telemarketing": "2.x",
    "vtex.order-placed": "2.x",
    "vtex.stack-layout": "0.x",
    "vtex.responsive-layout": "0.x",
    "vtex.slider-layout": "0.x",
    "vtex.iframe": "0.x",
    "vtex.breadcrumb": "1.x",
    "vtex.sticky-layout": "0.x",
    "vtex.store-components": "3.x",
    "vtex.store-drawer": "0.x",
    "vtex.store-link": "0.x",
    "vtex.styleguide": "9.x",
    "vtex.tab-layout": "0.x",
    "vtex.add-to-cart-button": "0.x",
    "vtex.search": "2.x",
    "vtex.store-icons": "0.x",
    "vtex.store-header": "2.x",
    "vtex.checkout-summary": "0.x",
    "vtex.store-footer": "2.x",
    "vtex.disclosure-layout": "1.x",
    "vtex.product-list": "0.x",
    "vtex.product-price": "1.x",
    "vtex.modal-layout": "0.x",
    "vtex.overlay-layout": "0.x",
    "vtex.store-video": "1.x",
  }
}
```

#### Peer Dependencies

```json
"peerDependencies": {
    "vtex.mega-menu": "2.x",
    "vtex.reviews-and-ratings": "3.x"
}
```

### Custom component

```json
{
    "itgloberspartnercl.whatsapp-button": "0.x",
    "itgloberspartnercl.bullets-diagramation": "0.x",
    "itgloberspartnercl.add-to-cart-info": "0.x",
    "itgloberspartnercl.custom-department-search": "0.x",
    "itgloberspartnercl.pdf-reader": "0.x",
    "itgloberspartnercl.quick-order": "0.x",
    "itgloberspartnercl.special-diagramation": "0.x"
}
```

### Documentation to be considered
- [Gitflow](https://www.atlassian.com/es/git/tutorials/comparing-workflows/gitflow-workflow)
- [Code Standard](https://github.com/ITGlobers/CodeStandard)
- [Semantic Commit](https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716)
