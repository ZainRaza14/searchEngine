# searchEngine
 A web search engine that allows users to retrieve relevant information, thereby identifying relevant pages on the web containing given keywords. 
 
All the code is implemented in the attached jupyter notebook named as "mySearch"

My implementation is the same as described in book on page 679.

First, I have a class for Tries which is for the set of index terms, where each external node 

stores the index of occurence list of associated terms.

I have another class named as "myInvertedIndx":

This class is for storing the core information stored by the search engine in a dictionary having

key value pairs with w and L. w being the words and L being the collection of references to pages

containing those words. Index terms are the words in this dictionary.

Finally the class named as "mySearch" searches for the words in the Tries. There are 

occurrence lists in this class implemented as lists. 

I have also implemented a simple ranking which ranks the pages simply by just returning them 

with respect to terms frequency. 
