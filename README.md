# _Word Counter Project_

#### _Independent Project for C# week 1, 11.16.2018_

#### By _**Kenny Wolfenberger**_

## Description

_A C# application that takes both a word and a sentence from a user. It then checks how frequently the word appears in the sentence and returns this information to the user._

## Setup/Installation Requirements

* _Clone this repository_
* _Install Mono and .NET Framework_
* _Open the folder and run Program.exe in Mono_
* _Follow command prompts in Terminal_

## Support and contact details

_Kenny Wolfenberger - kennywolfenberger@gmail.com_

### Specs
| Spec | Input | Output |
| :-------------     | :------------- | :------------- |
| Create instance of WordSentence class |new WordSentence instance | Type of new instance == type of WordSentence  |
| WordSentence class can hold and return a word string | "coffee" |  "coffee" |
| WordSentence class can hold and return sentence string | "I like coffee" |  "I like coffee." |
| User can set a word | "car" | "car" |
| User can set a sentence | "My car is a fast car." | "My car is a fast car." |
| Program can identify when the word is also in the sentence | "coffee", "I like coffee" | true  |
| Program can identify when the word is not in the sentence | "new", "string from user" | false  |
| Program counts the number of times the word is in the sentence | "coffee", "I like coffee" | 1  |

## Technologies Used

* _C#_
* _.NET_
* _MSTests_

### License

*This software is licensed under the MIT license.*

Copyright (c) 2018 **_Kenny Wolfenberger_**


