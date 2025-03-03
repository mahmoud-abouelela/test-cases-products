# test-cases-products

 # Get all products
  RESPONSE:

  ![image](https://github.com/user-attachments/assets/34027cf6-22d5-4998-8415-836ad5bd8a24)

## Get product by id

   RESPONSE: 

   
   ![image](https://github.com/user-attachments/assets/937cc087-6499-4f60-84dd-d40295027643)


  ## Get product with existing id 


   RESPONSE: 
   
   
   ![image](https://github.com/user-attachments/assets/81e9f7ce-8968-44cd-ac26-272cf4ea958f)

   
 # Create a product
   
   1- create product with options and variants
      
   RESPONSE: Sucess
 
     
  ![image](https://github.com/user-attachments/assets/3d40abf4-31ff-47cb-b671-a372df34cc89)

  2- Create a product with only options and no variants

  RESPONSE: Throws error

  
   ![image](https://github.com/user-attachments/assets/abe40f3d-550a-4b3b-bb0c-5a1ba54d39d7)

   3- Create a product with no options but with variants

   RESPONSE: Throws error

   ![image](https://github.com/user-attachments/assets/15cdc7a5-5451-4ff6-95fd-e5119d131ff6)

   4- Create product with no options and no variants

   RESPONSE: Success

   ![image](https://github.com/user-attachments/assets/8eef218f-4b08-4d02-a068-5e078ed64eef)


 # Update a product
  
  1- Remove an option (498)

  
   BEFORE DELETION:
   
   
   ![image](https://github.com/user-attachments/assets/5997fbc2-11b6-4999-8010-72619eb53789)


   AFTER DELETION:

   ![image](https://github.com/user-attachments/assets/f4847dc4-f927-43c1-af4c-94b2493eae89)

  2- Remove variant 
   BEFORE DELETION:
   
   
   ![image](https://github.com/user-attachments/assets/217f24b9-c998-4b16-9f9b-3df74cab8aa8)


   AFTER DELETION:

   ![image](https://github.com/user-attachments/assets/05503c4c-ae11-4527-ae7c-706d115e65fd)
   

  3- Add options with variants

   BEFORE ADDING:

   ![image](https://github.com/user-attachments/assets/809fd20d-7d12-417e-8d9b-f75c0e1e05e0)

   AFTER ADDING:

   ![image](https://github.com/user-attachments/assets/8f0f4dff-90a5-4ffc-a379-c2ed17605a71)

  4- Change option display order and values order
   BEFORE CHANGE:

   ![image](https://github.com/user-attachments/assets/ed8ae69a-85fb-4a33-a143-dce373873204)


   AFTER CHANGE:

   ![image](https://github.com/user-attachments/assets/894015d4-cf66-4a91-8310-3b313582140f)


  6- Update option value with existing name
  
   ![image](https://github.com/user-attachments/assets/e42df204-db7d-4b7f-953f-ff367fcfd1a9)

  
  5- Delete an option , insert it back again with variants , change option name and edit variants based on the change
  
  7- Update variants options to be the same
  
   - **NO CHANGE**


  8- Delete variant and try to add it again

  
   BEFORE INSERTING AGAIN
   
   ![image](https://github.com/user-attachments/assets/b01d53ad-c500-404b-86f4-f302846f2b06)

   AFTER INSERTION

   ![image](https://github.com/user-attachments/assets/47410db9-ba9c-406e-ae8e-bdb19862b4ab)

 9- Update variant name manually 

   - **NO CHANGE**

10- Update variant price to be negative

  - ** REQUIRE VALIDATORS **

    ![image](https://github.com/user-attachments/assets/31e73417-4da3-4d4b-bd19-208c94aa2688)


