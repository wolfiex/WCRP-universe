

<section id="info">

# Source Type  (universal)

|  | uri |
| --- | --- |
| Type | `wrcp:source-type` |
| Pydantic class | [`source_type`](https://github.com/ESGF/esgf-vocab/blob/main/src/esgvoc/api/data_descriptors/source_type.py): SourceType |
| | |
| JSON-LD | `universal:source-type` |
| Content | [https://wcrp-cmip.github.io/WCRP-universe/source-type](https://wcrp-cmip.github.io/WCRP-universe/source-type) |
| Developer Reoo | [![Open in GitHub](https://img.shields.io/badge/Open-GitHub-blue?logo=github&style=flat-square)](https://github.com/wcrp-cmip/WCRP-universe/tree/main/src-data/source-type) |


</section>
    

<section id="description">

## Description

</section>


<section id="schema">

## Content Schema

- **`id`** (**str**) 
  << No description in pydantic model (see esgvoc) >>
- **`type`** (**str**) 
  << No description in pydantic model (see esgvoc) >>
- **`drs_name`** (**str**) 
  << No description in pydantic model (see esgvoc) >>
- **`description`** (**str**) 
  << No description in pydantic model (see esgvoc) >>





</section>   

<section id="usage">

## Usage

### Online Viewer 
To view a file in a browser use the content link with `.json` appended. eg. https://github.com/wcrp-cmip/WCRP-universe/tree/main/src-data/source-type/.json

### Getting a File. 

A short example of how to integrate the computed ld file into your code. 

### Framing
```js
frame = {
            "@context": "https://wcrp-cmip.github.io/WCRP-universe/source-type/_context_",
            "@type": "wcrp:source-type/",
            "keys we want": "",
            "@explicit": True

        }
        

print(usage)

```

```python

import cmipld
cmipld.frame( universal:source-type )

```
</section>

    