# Build-Restocking-Functionality
 A small webApp for product restoking using Strapi to consume a local API

 To initiate the project run **http-server -c-1**
 The button "Restock Products" in the webApp use the input beside it to call an API with a list of products that follows this structure:

 ```
{
    name: string,
    cost: number,
    country: string,
    instock: number
}
 ```
