# DevLibrary


Greeting Fellow Developers we are making this repo just to keep our self's updated with latest working standards, sharing our custom librabris and tip & tricks  

1) Please feel free to update this when ever you feel like.
2) When your  are  adding a new library or updating it, please make your you describe it well.
3) Please try to bake your code with proper syntax, indentation, standard naming convention etc, you know it well.
4) Please add branch if you are adding a new type of librabry for eg: javascript helpers will goes in javacript librabry.
5) Please always show example  something like this   

```{

 //init class 
  const http = new EasyHTTP();
  
  
  // for get call
  http
  .get("https://jsonplaceholder.typicode.com/posts")
  .then((data) => console.log(data))
  .catch((err) => console.log(err));

}
```
##### keep learning Kudos 
---
## naming convention
___

| Syntax      | Description | example code     |
| :---        |    :----:   |          ---: |
| Private Field    | Should be started with an underscore and lower case and camel case   |   private Int _userName  |
| Public Field   | The first letter of each word should be in Pascal Case   |  Public Sting NetworkManager   |
| Protected Field   | The first letter of each word should be in Pascal Case   |  Protected Sting GameManager;   |
| Internal Filed   | TThe first letter of each word should be in Pascal Case   | Internal Sting ScoreManager;   |
| Methods     | The first letter of each word should be in Pascal Case.        | Public string GetScore(string playerId){//…………….}  |
| Class    | Always use PascalCase for class names.        | public partial class  Player : Score  {  //...  }  |
| Interface   | Always use the letter "I" as a prefix with the name of an interface. After the letter I, use       | public interface   IAvailabelCoins{  bool IsAvailabe();}  |
| Local Variable  | Always use camel case with method arguments and local variables | public string GetPosts(string score)  {  int numberOfPost = 0;   }  |
| Enum   | Always use pascal case | enum QuestName{BPDrug,Pulse}|
| Namespace  | Always use pascal case | Namespace TML.ScoreManager|
___

## folder structure


[^1]: - is used to show levels  root *,  ** level 1, *** level2, *** level3

```
{
  root*
      ** assets
       *** css
       *** js
       *** images
       *** vendor (this can used to add 3th party librabry need in both userpanel and adminpanel
       *** admin
        **** css
        **** js
        **** images
        **** vendor (spefic to admin panel)
      ** controllor
        *** admin
          **** demo contoller
        *** pages (default controllor)  
      ** views
      
      ** model
}
```


## Libraries 

| Libraries      | BranchName | 
| :----:        |    :----:   | 
| JavaScriptLibrary        |    :----:   | 

