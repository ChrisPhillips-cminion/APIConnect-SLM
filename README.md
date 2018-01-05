# APIConnect-SLM

# User Defined Policy to allows SLM shaping

The default shaping size is currently set to ten concurrent connections. If you wish to change this modify the export.xml.

## The build script


To build the source run
```mkdir out && sh build . slm ```

this will then produce a zip file in the out directory.

This can then be loaded into a catalog in APIC.

## TODO

Write a node wrapper that will take options from a user and create a custom SLM policy depending on those criteria.
