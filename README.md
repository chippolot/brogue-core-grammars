# Brogue Core Grammars
A core set of grammar files for use with [Brogue](https://github.com/chippolot/brogue).
Translated from [@dariusk's](https://github.com/dariusk) [Corpora](https://github.com/dariusk/corpora);

## Usage

First insall [Brogue](https://github.com/chippolot/brogue) and the core grammar set:
```
npm install --save brogue brogue-core-grammars
```

Then include the core grammars in your grammar file:
```
{
    _includes: [
        'path_to_node_modules_folder/brogue-core-grammars/grammars/core.grammar',
    ]
}
```

## Included Grammars
You are encouraged to explore the `grammars` folder to find all of the included grammars. 
The `core.grammar` file includes all of the grammars in this repo, so you may aslo choose to 
include them individually to reduce parsing time.