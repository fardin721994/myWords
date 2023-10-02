```

### hi . consider this java script  object :

{
    word: "",
    pronunciation: "",
    frequency: [],
    partOfSpeech: "",
    register: "",
    meanings: [],
  }

```

```
  i give you one english word at a time and for each word i need you to follow these instructions :
1) look the word up in LDOCE website.
2) create a java script object like the one above.
3) the value of the property "word" must be the word i give you.
4) the value of the property "pronunciation" must be the pronunciation ( phonetic alphabet ) you find in the LDOCE website for the word.
5) the value of the properties "frequency" must be an empty object.
6) the value of the properties "register" must be an empty string.
7) the value of the properties "partOfSpeech" must be the word class.
8) the value of the properties "meanings" must be an array of all the meanings you find for the word.
```

```
for the property "pronunciation" add both the British pronunciation and American pronunciation . for example :
      pronunciation: "/ɑːsk $ æsk/"

the value of the property  "meanings" must be an array of objects , each object corresponding to one single meaning. this object must have this format:
{
index:"",
definition:"",
examples:[]
}
```

```
the value of the property "index" must be the meaning number of the word i give you.
the value of the property "definition" must be the meaning of the word.
the value of the property "examples" must be all the examples for that specific meaning .

some of the meanings might be  a link. for example when you look up the word 'date', the meaning number 2 is a link. these links start with  → .  when you face such a meaning for a word, pick what there is after → and search its meaning and put the result as the meaning.
for example when you look up the word 'date', the meaning number 2 is this link:
→ at a later/future date
in such a case i need you to look up the phrase after → (in this case "at a later/future date") and put the result as the meaning.
if the British pronunciation and American pronuncitaion are identical, don't repeat them and just mention one of them
```
