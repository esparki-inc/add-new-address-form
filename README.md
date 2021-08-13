Removing the popup modal from Shipping Address in Checkout 

 

Overview: 

When the customer tries to add a new shipping address, a popup form appears where he can define the new shipping address details on checkout page. The order of customer will be shipped on this new address. The purpose of this module is to remove the appearing popup on clicking +New Address button. After the pop is removed the form will appear below the button and the form works same as it performs in the popup modal. 

When new address is added there is option to edit the new shipping address. The edit button opens the popup but in this module that popup won’t appear and the form will open below the Shipping address details and the customer can edit the new shipping address details. 

 

Features: 
The popup modal will be removed and the form can be seen below the new address button and the save button can add the new shipping address in the address book in checkout page and cancel button will disappear the shipping address form. 

 
--Instruction To Install the Extension 

add this module under app/code/EparksInc/AddNewAddressForm

...Under your root folder run the following commands: 

   composer require espark/add-new-address-form 

   php bin/magento setup:upgrade

   php bin/magento setup:di:compile 

   php bin/magento cache:flush 

 

 

 

 

 

 
