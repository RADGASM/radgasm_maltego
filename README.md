### Welcome! I'm still learning so excuse the formatting if it looks off.


## Maltego for OSINT investigations:
Maltego is a data mining tool that mines a variety of open-source data resources and uses that data to 
create graphs for analyzing connections.

1. You'll need to download Maltego into your VirtualBox directly from their website. Find the download based on your OS of which I'm using Kali == Linux. This is the company that created Maltego: https://www.paterva.com/downloads.php

2. The download should be relatively quick. Open up the terminal to the 'Downloads' folder and unpack the file via 'sudo dpkg -i [file-name]' command: 
  ![Maltego1](https://user-images.githubusercontent.com/31832154/72209919-07d4c980-3482-11ea-8c12-d9b47b7f3502.PNG)

You can also find it as such:

  ![Maltego2](https://user-images.githubusercontent.com/31832154/72209928-276bf200-3482-11ea-9d86-1d3d313ad766.PNG)

Find your product when you open Maltego:

  ![Maltego3](https://user-images.githubusercontent.com/31832154/72209945-5b471780-3482-11ea-8c3b-dc4d43d81b48.PNG)


3. Create a new account:

  ![Maltego4](https://user-images.githubusercontent.com/31832154/72209952-6d28ba80-3482-11ea-8135-fddd43e36c2c.PNG)
   

After you create a new account, you'll see the following:

  ![Maltego5](https://user-images.githubusercontent.com/31832154/72210364-250c9680-3488-11ea-9bd0-a5738e8595c6.PNG)
  ![Maltego6](https://user-images.githubusercontent.com/31832154/72210366-2dfd6800-3488-11ea-99ad-3347410aad77.PNG)
  ![Maltego7](https://user-images.githubusercontent.com/31832154/72210369-381f6680-3488-11ea-973f-056c32c1b6a5.PNG)


4. You'll get to the following screenshot after clicking through. Open up a new machine:
  ![Maltego8](https://user-images.githubusercontent.com/31832154/72210373-5d13d980-3488-11ea-9a38-95626953b7c1.PNG)
 ![Maltego8_2](https://user-images.githubusercontent.com/31832154/72210851-65bbde00-348f-11ea-8643-8aa1a258703f.PNG)
 ![Maltego9](https://user-images.githubusercontent.com/31832154/72210816-03fb7400-348f-11ea-9d4b-5e8ce986074c.PNG)
 
 
5. Create a new graph:
  ![Maltego10](https://user-images.githubusercontent.com/31832154/72210821-0cec4580-348f-11ea-8674-60b9fba0c508.PNG)


Pay attentinon to the Entity pallet:

  ![Maltego11](https://user-images.githubusercontent.com/31832154/72210825-1fff1580-348f-11ea-99ad-4e5d96ea0112.PNG)
  

6. Drag and drop domain and double click to change the name to the domain/site of your choosing including the layout. I am using 
Aol.com as an example in the screenshot below:
  ![Maltego12](https://user-images.githubusercontent.com/31832154/72210926-630db880-3490-11ea-8be6-0d2386cb84b8.PNG)
  
  
  Right click and find ‘all transforms’ (usually on top) and click the >> button right next to it which will showcase connected 
  websites to your domain:
  ![Maltego13](https://user-images.githubusercontent.com/31832154/72210929-6b65f380-3490-11ea-8a17-076e9274bf18.PNG)
  ![Maltego14](https://user-images.githubusercontent.com/31832154/72210930-73259800-3490-11ea-9315-b45802ddd7ef.PNG)


7. Check out the different layouts under 'Layouts' as it loads or transforms:
  ![Maltego15](https://user-images.githubusercontent.com/31832154/72210932-7c166980-3490-11ea-8ed0-ccafe574dc60.PNG)

   This makes it easier for a user to view relationships in a less cumbersome, text-heavy way.
  
  
  After Transform reaches 100% it will show all the related websites for your domain of choice on the right hand side. 
  Click through each to see where it falls under the domain:
  
   ![Maltego16](https://user-images.githubusercontent.com/31832154/72211005-a157a780-3491-11ea-8cde-f7eeb4719ebc.PNG)


8. If you zoom out, you can also see a color guide tied to your domain:
  
  ![Maltego17](https://user-images.githubusercontent.com/31832154/72211007-a9174c00-3491-11ea-8759-2a5575340359.PNG)
  
  
If you want to run a specific machine that does a specific behavior only, go back to your panel and select ‘company stalker’ as an example:


  ![Maltego18](https://user-images.githubusercontent.com/31832154/72211019-d237dc80-3491-11ea-94d1-1d547c7f0c9c.PNG)


  
  
