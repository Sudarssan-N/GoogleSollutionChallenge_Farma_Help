# GoogleSollutionChallenge_Farma_Help

  ## Front End 
  
  1) Navigate to the frontEndApplication folder and open the lib folder
  2) Use the command in the terminal "Flutter pub get"
  3) Once that is complete all the modules have been built and you can "flutter run" to compile the application
  4) Create a mobile emulator if necessary else go ahead with chrome.
  
  ## Back End
  
  1) Open the app and all the API are hosted on the Microsoft Azure Server 
  2) You can view all the files in the backEnd folder
  
  ## Machine Learning 
  
  ### 1) Model Structure
    We have use CNN based architecture using the keras module, with 11 class input and 1 output that is the soil mositure prediction 
    11 Classes 
      0% - Dry state
      10% - Moisture
      20% - Moisture
      30% - Moisture
      40% - Moisture
      50% - Moisture
      60% - Moisture 
      70% - Moisture
      80% - Moisture
      90% - Moisture
      100% - Moisture
      >100% - Excessive Water Stagnated
  ![image](https://user-images.githubusercontent.com/63306215/229866480-970dc81d-32a2-452f-a40b-1da8930f03e5.png)

    
  ### 2) Dataset
    We have collected the data set manually and labled them as there is no available data for this problem 
    Types of Soil
      1) Red - 540 images
      2) Black - 540 images
      3) Alluvial - 540 images
  
  ### 3) Model Progress 
  We have woked on several combinations and found this to be the best working.
  ![image](https://user-images.githubusercontent.com/63306215/229866584-653e081d-7a33-4098-8ba0-25303aa4841c.png)
  ![image](https://user-images.githubusercontent.com/63306215/229866634-51b40d60-c3ea-4919-baed-a5ebf89f87ad.png)
  
  ### 4) Working Correlation 
  ![image](https://user-images.githubusercontent.com/63306215/229867099-e9362c03-b319-43e6-9599-ea72c30df222.png)
  
## System Architecture

![image](https://user-images.githubusercontent.com/63306215/229867408-850eea32-ff5a-4e9a-b348-3f4020dc3c93.png)



    
    
