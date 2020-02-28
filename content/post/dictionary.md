+++
title = "English/Spanish Dictionary in C"
date = 2017-01-01T00:00:00

+++

{{< figure library="1" src="IntroData.png" title="Initial Window" >}}

# Project Overview
  * This project is an English to Spanish dictionary that uses a hash function to store the key words and translations. As shown in the image above, once the file is run, the user is asked for a file name. In this case, the file is called Spanish.txt. It contains a list of words in english followed by thier spanish translations. Once the file is opened, the words are indexed using a hash function. The program then displays a few stats such as the total number of hashed items, the average number of probes required to find an empty spot to store an item, the average number of probes and the highest probe value. In this case, there is plenty of room for improving the hash function as the number of average probes is about 8. Then the progam displays the number of items indexed at each probe value. After, the user is given an option to search for a word, add a word, delete a word and quit. 
  
{{< figure library="1" src="search.png" title="Input file name window" >}}

  * If the user selects the search option, they will be asked for a word to search for. As shown above, if the word is found, the number of required probes is shown, along with the translations. If the word is not found, the user will be informed that the word was not found and the number of probes required to complete the search. 
  
{{< figure library="1" src="Insert1.png" title="Error Message" >}}

  * When the user selects the insert option, they will be asked for the word along with the translation. As above, if the word already exists, the new translation will simply be added.  
  
{{< figure library="1" src="Insert2.png" title="Error Message" >}}

  * In the second example of insert above, when the word to be inserted is not found to already exist, both values are inserted into the dictionary. 
  
{{< figure library="1" src="delete.png" title="Error Message" >}}

  * The user can also select a delete option. In this example, the user deletes hunter which was previously entered as a new translation. When searched, the program shows that the word was not found and the required number of probes for the search.
  
{{< figure library="1" src="quit.png" title="Error Message" >}}

  * The last option is to quit the program. Once selected, the program displays the total number of probes and the average number of probes for the current session. 
