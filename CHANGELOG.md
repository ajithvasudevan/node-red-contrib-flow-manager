#### 0.6.0 Flow handling enhancements

- Performance improvements during deploys. 
- Support for envnode overriding using node name (not only by node id). 
- On Demand flow loading using RESTful requests (apart from filter-flows).
- Retrieving state of flows using RESTful requests (isDeployed/hasUpdate/onDemand).  

#### 0.5.2 Flow handling enhancements

- Performance improvement during initial boot.
- Fix for project mode when creating first project.

#### 0.5.1 Flow handling enhancements

- Flow renaming/removal triggered automatically by deploy.<br/>No need to delete/rename the flow in the file-system manually.
- Renamed "Show Flows" in filter popup to "Load Flows", better representing what it does.

#### 0.4.5 Bug Fix

- Ignoring non json/yaml files in flows directory

#### 0.4.4 Features & Improvements

- Replaced deprecated dependency fs-promise with fs-extra
- Project mode support
- Removed "Save Flow" button (triggered after each deploy)
- Removed dependency on deprecated library "asyncawait"

#### 0.4.3 YAML format

- Support for flow files in yaml format

#### 0.4.2 EnvNodes Visual Revert

- EnvNodes functionality improved<br/>Changes to envnode controlled properties are automatically reverted also on UI side.

#### 0.4.1 EnvNodes

- EnvNodes functionality improved<br/>Changes to envnode controlled properties are automatically reverted on NodeJS side.

#### 0.3.1: Maintenance

- Added missing keywords in package.json to appear in Node-RED library.

#### 0.3.0: First Release