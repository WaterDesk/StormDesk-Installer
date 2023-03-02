# StormDesk

StormDesk, a fully functional drainage modelling software based on EPASWMM, covers the whole process of 1D Hydrologic and Hydraulic modelling process. In addition, a lot of extra efforts have also been made after adopting the experience of many front-line engineers, to improve user interface and enhance toolboxes, which allow users to focus on the engineering.

As a sister product of [WaterDesk](https://github.com/WaterDesk/WaterDesk-WS), StormDesk is <b>FREE</b> too!

![StormDesk](./images/StormDesk_01.png)

## Release Notes

### version 2.0.0

- Add <b>Designing</b> module for rainwater pipeline degign with inference formular method, achieving seamless integration between network design and model simulation
- Add rainstorm intensity formula editor
- Enhance importing dxf file as Conduit, Subcatchment, Line, and Polygon
- Some performance and UI improvements, and some bug fixes

### version 1.2.0

- Add general Line object
- Add Velocity SCADA object
- Graph: display precipitation graph together with object results
- Multiple graph: add scada object, display precipitation graph together with other objects
- Merge model file (.wsm)
- Add navigation mode settings in status bar: highlight, move, zoom with different levels
- Support hot start for simulation
- Support to covert objects in shape background files to model objects, such as junction, conduit, subcatchment, point, polygon, and etc.
- Data integrity check, data evaluation
- Get raingage rainfall data from scada
- Inference the invert elevation of junction
- Time series expression editor; convert scada data to time series by expression
- Model result precision analysis
- Allow not to load result when open a model
- Some performance and UI improvements, and some bug fixes

### version 1.1.0

- Upgrade EPASWMM engine to 5.2.0
- Add Streets cross-section, Inlet object, and [INLET_USAGE] property of conduit, and etc.
- Add Streets model example into the installer
- Quick evaluation of Streets flooding
- Runoff Quantity Continuity analysis
- Data Import: import lines or polylines from DXF file as conduits
- Add Customer Objects with water usage info which can be allocated to adjacent junctions automatically as DWF.
- Support to batch convert objects to other types of node or links
- Support to move network by adjusting X,Y values
- Add a summary table about invisible objects in the right project panel
- Some performance and UI improvements, and some bug fixes

### version 1.0.0

- Full capabilities of EPA SWMM5
- Data Import: INP, Excel, and Shape Files
- Data Export: INP, Shape Files (by object types or selection set)
- Data Table: display data table for all objects or selected objects, allow user to batch edit properties (plus, minus, divide, multiply, assign); data table for Subcatchment Infiltration Data, Node Inflows Data
- Support adding image or shape files as background
- Support online map (Baidu Map and Baidu Earth), allow user to match model to online map by specifying base and reference positions
- Quick chart graph to display result charts for selected objects
- Multiple charts graph to display multiple result properties and multiple objects
- Profile graph for selected links, and bi-direction, up-stream, down-stream profile
- Quick label and custom label setting for objects
- Quick legend, and quick view with surcharging and flooding objects
- Calibration Tool: unique SCADA management module for Flow SCADA and Level SCADA and convenient calibration tools.
- Selection Set
- Tools:
  - Purge conduits and junctions belong to branches
  - Trace up / Trace down
  - Create subcatchments by Thiessen polygons
  - Recalculate conduit's length
  - Recalculate subcatchment's and polygon's area
  - Check the duplicated links
  - Check the duplicated nodes
  - Connection analysis to find all sub-networks
  - Infer link's direction
  - Infer conduit's diameter (or width)
  - Infer ground elevation of nodes
- Search Bar
- Toolbar: Pan, Zoom In, Zoom Out, Zoom Extent, Zoom Previous, Zoom Next, Select, Polygonal Select, Identify, Add Text Label, Measure Distance, Trace Up, Trace Down, Profile Selection, Quick Chart, Refresh, Delete
- Status Bar:
  - Simulation Status
  - Flow Unit
  - Operation Display
  - Selection Mode: Normal and Cycling (allow user to select one from overlapped objects)
  - Scale Ratio
  - Coordinates
- Allow user to add note as history notes when save
- Manual, Video, FAQ
