#### Problem 1:

- Description: Problem 1 is in the head it is missing both a title and meta data. 

#### Problem 2:

- Description: We see a performance hit when loading the large image with a load time of 3200ms.

#### Problem 3: 

- Description: Adding the whole Jquery library for a single use in the js file is bad for the performance.

#### Problem 4: 

- Description: Style in the head is not being used and therefore not needed in the file.

#### Problem 5: 

- Description: Using the !important is not needed in the code here.

#### Problem 6: 

- Description: None of the classes are used in the html file so it is just extra code in the css file.

#### Problem 7: 

- Description: Here the image is being made into a very large width making the img load very long.

#### Problem 8: 

- Description:It is to specific and should only use the h2 since there is only one in the file.

#### Problem 9: 

- Description:The async on this file makes it load long and could potentially shift elements on the page.

#### Problem 10: 

- Description: There is a random block of code placed here with no use in the file and takes a long run time because of how many times it loops.

#### Problem 11: 

- Description: Here we are using the $ from Jquery when we should use querySelector instead of downloading the whole Jquery for this one time use. 

#### Problem 1:

- Solution: Decide a title and add meta data

#### Problem 2:

- Solution: We could add a height and width to the image to help with load time.

#### Problem 3:

- Solution: Remove the Jquery script

#### Problem 4:

- Solution: Remove the extra in file css

#### Problem 5:

- Solution: Remove the !important

#### Problem 6:

- Solution: Remove the extra code and unused classes in the css

#### Problem 7:

- Solution: We can use a width of auto or even set the size to be a certain size smaller than the current value

#### Problem 8:

- Solution: Remove the extra text that is before the h2 to make it less specific.

#### Problem 9:

- Solution: 

#### Problem 10:

- Solution: Remove the extra block of code, if wanted then you can lower the number of times that it loops.

#### Problem 11:

- Solution: Remove the jquery line of code and add document.querySelector in its place.

#### Reflect

I learned that some errors are more heavy on the performance. The !important is something I hadn't seen before and overrides values for a specific css. I also learned its not necessary to be super specific for css files such as in problem 8.
