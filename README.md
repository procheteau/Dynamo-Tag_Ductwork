# Dynamo-Tag_Ductwork

<img src="images/graph.png" width="500" >

By applying Dynamo and Python scripts, I was able to automate the tagging of in a 3D Autodesk Revit building model.
Revit already has a tool for tagging all the ductwork elements in a view, but it tags all duct elements (elbows, risers, very short branches, ductwork that has already been tagged). This ends up being a mess on plans and is counterproductive.

The Tag_Ductwork script utilizes the Revit API to locate all untagged ductwork in a model and applies a tag where
appropriate.

<img src="images/before-tag.png" width="400" >
<br>

*Untagged and sufficiently large ductwork elements are identified and tagged*
<img src="after-tag.png" width="400" >
