---
layout: archive
title: "Project"
permalink: /project/
author_profile: true
---

# Abstract
I plan to upload some of my projects to this website, including those I completed during university courses as well as my personal side projects. I’m still deciding what else to include here—maybe some useful tools (well, at least they’re useful to me...). The source codes will be available on GitHub, but I’ll also provide some usage instructions here.

{% include base_path %}

{% for post in site.project reversed %}
  {% include archive-single.html %}
{% endfor %}


### <details>
  <summary>[IERG2080 Project: 2D bitmap editor](https://github.com/dizzyryan/CUHK-CS-Notes/blob/bf9a807f64c491d62685a233bd8f789d982280ca/IERG2080/proj.c)</summary>
    You can compile the code by
    ```
    gcc proj.c -o proj -lcurses
    ```

    Or by creating a Makefile
    ```
    make:
        gcc proj.c -o proj -lcurses
    ```

    Then, you can use the program by
    ```
    ./proj [in=in_file] [out=out_file]
    ./proj [out=out_file] [in=in_file]
    ```
    Both arguments are optional. Yet, the phase in= or out= must be provided if the corresponding argument is used. in_file is the input file name, and out_
    file is the output file name.
</details>



# Personal Creation