Dataset should be downloaded with this link into the directory of the jupyter file:
https://drive.google.com/file/d/1SQ4L0tCT1rVGV7u_0AvAwrPNLw2l_uAn/view?usp=sharing

# Pattern Recognition and Data Analysis for Behavioural-Economics
The dataset contains rows which represent a Product Page of a specific product viewed during a user visit and also the information whether the users checked out in the end. The user can view  the same product multiple times during the same visit, hence multiple according rows will be shown.


## Dataset variables description:
⦁	date: The date when the user visited the Product Page.

⦁	productID: Is the general identification of the product visited. Each product has a productID which represents a product with a list of possible sizes. Each product with a productID when a size is selected has also an id which is used to represent the specific product. If a product is placed in the Cart or purchased, then we use the id to identify it, as now has the size selected.

⦁	tempSessionID: Is the identification of the user’s visit. During a visit, the user views different Product Pages, viewers the Cart and in the end can also check out. 

⦁	globalControl: Users who have globalControl False see the incentives selected for that user, whereas True the selected incentives are not shown. This is used to compare users who see the shown selected incentives vs users who didn’t see the selected incentives. Compare apples with apples

⦁	cart:add: During that  Product Page viewed of the product with productID, a user can place the product in the Cart. The variable shows how many times during that Product Page Viewed did the user placed that product in the Cart.

⦁	productsAddedToCart: Contains a list of product specific id which were placed in the Cart during that Product Page viewed. This is important to analyse in the end whether the user bought that product or not which was placed in the Cart during this Product Page view.

⦁	price: The price of the product shown during that Product Page viewed.

⦁	revenue: skip it

⦁	totalSaved: Total sume the user saved when he purchased sales (Products that are on sale) products.

⦁	saleProducts: Total sale product purchased.

⦁	nonSaleProducts: Total non sale products purchased.

⦁	totalRevenue:  In case the user viewed that Product Page and at the end of the visit checked out, the revenue is the total sum of the purchase.

⦁	checkout: 1 if the user viewed that Product Page and checked out in the end, and 0 if not.

⦁	amount: Total amount of that product purchased in the end.

⦁	'2.1.1', '2.6.2', '2.4.4', '2.24.1', '2.9.1', '2.91.1', '2.9.5', '2.4.2': These are the incentiveIDs. Each incentive has an IncentiveID. These variables show whether these incentives were shown during the Product Page view

 
