# Localize Multiple Language 

Localize Multiple Language is a simple Javascript library which can be used to build website which support multiple language which help in code readability and standardize it.

## Installation

Use package manager npm(https://www.npmjs.com) to install the library Localize Multiple Language.

```bash
npm install localize-multi-language
```

## Usage

```python
import {localizeLanguage} from "localize-multi-language";

var multiLanguageJson = {"english" : {"HELLO":"Hello"} , "hindi" : {"HELLO":"नमस्ते"}}

localizeLanguage(multiLanguageJson, "HELLO" , "english")  # return Hello 
localizeLanguage(multiLanguageJson, "HELLO", "hindi" )    # return नमस्ते

```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

