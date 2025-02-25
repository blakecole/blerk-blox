# BLERK'S CUSTOM BLOX
A repository for my custom blox.

## Configuration Blocks
Each blox will have a corresponding YAML configuration block.

This block will likely be located in `./content/_index.md.`

### FEATURETTE
FEATURETTE displays a horizontal row of feature items.

The featurette has a title and subtitle, and each feature item has:
- Icon
- Title text
- Subtitle text

![A screenshot of the FEATURETTE block on a Hugo Blox website.](/blox/github.blakecole.featurette.png)

FEATURETTE uses following configuration block:
```
  - block: 'github.blakecole.featurette'
    content:
      title: "Programming Languages"
      subtitle: "A showcase of my favorites."
      feature:
        - name: "C/C++"
          description: "The pride of geeks everywhere."
          icon: "devicon/c"
        - name: "MATLAB"
          description: "Good but expensive."
          icon: "devicon/matlab"
        - name: "Python"
          description: "Clunky but free."
          icon: "devicon/python"
```


[Learn to Create a Custom Hugo Blox](https://github.com/HugoBlox/create-blox)
