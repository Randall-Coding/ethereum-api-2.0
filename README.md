# Completely remastered version.  

I made sure to make this code looks more like my best work rather than simply a first draft / MVP (ala Agile development).  

## Changes
* Code has been modularized, complex calculations are placed inside models when possible, minimal logic is placed in views.  
* Added additional transaction details (Total cost calculation, nonce/position, success has catch string if pre-Byzantium transacation).
* Variables in controller and model renamed for easier reading.  
* Mainnet/Ropsten buttons replaced with radio button. 
* Tests created for transaction model and for "basic search" integration.  Folder spec/models and spec/features.  Rspec/Capybara used.  
* New styles added, older styles deleted.
* Comments cleaned up and made to be concise.
* Code is fully functional on my computer / browser (Firefox) and will be deployed on Heroku ( ).
* Sqlite DB used

