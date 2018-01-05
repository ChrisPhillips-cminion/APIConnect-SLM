# APIConnect-SLM

# User Defined Policy to allows SLM shaping

The default shaping size is currently set to ten concurrent connections. If you wish to change this modify the export.xml.

## The build script

To build the source run
```mkdir out && sh build . slm ```

This will produce a zip file in the out directory.

This must be loaded into a catalog in APIC before it can be used.

To use this policy, edit the assembly of an API and drag the new SLM policy onto the canvas.

You will only be able to publish this API to the catalog that the policy was loaded into. 

## TODO

Write a node wrapper that will take options from a user and create a custom SLM policy depending on those criteria.
