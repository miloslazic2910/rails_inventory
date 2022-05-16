# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version
* ruby "3.1.2"
* Deployment instructions

1 $ git clone https://github.com/miloslazic2910/rails_inventory.git

2 cd rails_inventory   

3 bundle install

4 rake db:create

5 rake db:migrate

6 rails s


#################### Application Instructions #######################

1. Click on the link 'New item'

![image](https://user-images.githubusercontent.com/45238692/168510728-a5cfde66-aaa5-4bbd-a354-9121fe80e449.png)

2. Enter the desired values and select 'Create Item'

![image](https://user-images.githubusercontent.com/45238692/168510831-3cde5e66-e746-4128-98a8-98384a9c81ee.png)

3. On this screen you will see the product name, Qty, Price and discarded.  Discarded is set to false because the product is not deleted. If you want to edit this product, select the link 'Edit this item'

![image](https://user-images.githubusercontent.com/45238692/168510990-28edcd78-d04c-4bd4-b2c0-4bcf2a00cce0.png)

4. When finished select Update item. If you select 'Back to items' this link will take you to the home page where we list all of the items.

![image](https://user-images.githubusercontent.com/45238692/168511138-bd018b29-05e3-4308-9fa1-ebcfbde39340.png)

5. As you can see on this screen Qty is updated to 2000. 

![image](https://user-images.githubusercontent.com/45238692/168511416-2861ce6b-b9fe-408b-a7fa-425ae6f0e334.png)

6. In order to update or delete the product(item) select the link 'Show this item'

![image](https://user-images.githubusercontent.com/45238692/168511894-df395a0d-2451-418e-b7e8-e468cf0c172d.png)

7. On this screen you can delete the product(item) by selecting 'Destroy this item'

![image](https://user-images.githubusercontent.com/45238692/168512033-bccda3e4-bfd9-4ad4-a784-7d3f00931056.png)

8. When deleted a pop-up will apear with a confirmation prompt, select 'Yes'.

![image](https://user-images.githubusercontent.com/45238692/168512289-b9056fd2-71d1-417d-90da-6aa1c5659145.png)

9. After deletion, a green confirmation text will be visible in the top left corner. The field 'Discarded' is set to true and product is 'Soft Deleted', meaning it can be restored.

![image](https://user-images.githubusercontent.com/45238692/168512522-65c670f0-f533-4131-ad93-c1d17e614dec.png)

10. In order to restore the product, select 'Show this item' ==> 'Edit this item' ==> and finally select the radio button with the caption 'Restore Deleted record'(marked with checkmark)

![image](https://user-images.githubusercontent.com/45238692/168512800-4bf6d9f5-9145-4654-a675-fbab1e28f522.png)

11. We can see that the restore action is completed and the field 'Discarded' is updated to false.

![image](https://user-images.githubusercontent.com/45238692/168512886-4564c35d-f59b-4bf3-8d3b-b683c5e53999.png)

12. In order to delete the product permanently, we have to delete the product twice.

![image](https://user-images.githubusercontent.com/45238692/168513025-eba1a51e-b9d3-4fc9-b7a7-a18661bd1079.png)




























