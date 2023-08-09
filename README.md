# atlas_tuning_pyqgis
Create rectangles that involve the farthest points in the map so you can automatic adjust canvas when many blueprints in atlas.
The concept of this script is to provide a way to automatically scale and adjust the frame of each map or plan, especially when dealing with a large number of such maps. This script is designed to streamline the process of creating consistent and well-framed map visualizations by automatically determining the appropriate scale and frame for each map.

When dealing with a considerable number of maps or plans, manually adjusting the scale and frame for each one can be time-consuming and error-prone. This script aims to address this challenge by taking care of the scaling and framing process programmatically. Here's how it works:

1. **Automated Scaling:** The script calculates the optimal scale for each map based on the content it contains. It ensures that the content fits well within the designated frame without being too small or too large. This eliminates the need to manually adjust the scale for every map.

2. **Framing Adjustment:** The script determines the suitable frame size for each map. It ensures that the important features within the map are included while maintaining consistent spacing around the edges. This helps create visually pleasing and standardized map outputs.

3. **Batch Processing:** The real power of this script lies in its ability to process a large number of maps in one go. Instead of adjusting each map individually, the script can be applied to a collection of maps simultaneously. This is particularly advantageous when dealing with datasets containing numerous maps that need to be visualized consistently.

4. **Time and Consistency:** By automating the scaling and framing process, this script not only saves time but also ensures a consistent visual style across all the maps. This is important for maintaining a professional and uniform appearance, especially in cases where the maps will be presented to an audience or shared with others.

In summary, this script offers an efficient and systematic approach to automatically scale and adjust the framing of multiple maps or plans. Its utility becomes especially apparent when dealing with a large volume of maps, as it reduces manual effort, maintains consistency, and produces visually appealing outputs in a more streamlined manner.
