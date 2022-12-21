[toc]

获取可用的galley recipes接口

https://recipe.foodtruck-qa.com/recipe/galley-list



1. 获取可用的galley recipe ()

   Page: https://recipe.foodtruck-qa.com/recipe/galley-list

   ```
   put /ajax/galley-recipe 
   recipe_type: "TRUCK"
   status: "NO_WARNINGS"
   ```

2. 创建 wonder recipe

   page： 

   ```
   post /ajax/galley-recipe/cmVjaXBlOjE0OTk4OA%3D%3D/create-wonder-recipe
   	
   ```

3. 创建recipe item，分配餐馆

   ```
   get /ajax/wonder-recipe-version/800085701/create-item
   ```

4. 创建bom 

5. 

   

