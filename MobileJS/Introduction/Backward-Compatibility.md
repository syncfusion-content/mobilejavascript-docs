---
layout: post
title: Backward-Compatibility
description: backward compatibility
platform: Mobilejs
control: Introduction
documentation: ug
---

# Backward Compatibility

## Version 12.2 Changes

As a part of an effort to improve the user experience and provide consistent APIs across all the Syncfusion’s controls, significant changes are made to the API naming effective from Volume 2, 2014 release. The changes have been documented with mapping between the old and new API names to enable quick up gradation of any control. To migrate from Volume 1, 2014 or from earlier versions to this Volume-2, 2014, refer to the following specified API changes.

List of common changes made for all the components are as follows,

_Property Table_

<table>
<tr>
<th>
Member Type</th><th>
Old Enum Property</th><th>
New Enum Property</th></tr>
<tr>
<td>
Enum</td><td>
ej.textAlign = {        Center: 'center',        Justify: 'justify',        Left: 'left',        Right: 'right'    };</td><td>
ej.TextAlign = {        Center: 'center',        Justify: 'justify',        Left: 'left',        Right: 'right'    };</td></tr>
<tr>
<td>
</td><td>
ej.orientation = {    Horizontal: "horizontal",            Vertical: "vertical" };</td><td>
ej.Orientation = {    Horizontal: "horizontal",                 Vertical:"vertical" };</td></tr>
</table>


The other changes based on each components are as follows,__

<table>
<tr>
<td>
ejmAccordion</td><td>
ejmDatePicker</td><td>
ejmMaskEdit</td><td>
ejmScrollPanel</td></tr>
<tr>
<td>
ejmAutoComplete</td><td>
ejmDialog</td><td>
ejmMenu</td><td>
ejmSlider</td></tr>
<tr>
<td>
ejBarcode</td><td>
ejDigitalGauge</td><td>
ejmNumeric</td><td>
ejmSplitPane</td></tr>
<tr>
<td>
ejBulletGraph</td><td>
ejmGrid</td><td>
ejmPassword</td><td>
ejmTab</td></tr>
<tr>
<td>
ejmButton</td><td>
ejmHeader</td><td>
ejmProgressBar</td><td>
ejmTimePicker</td></tr>
<tr>
<td>
ejChart</td><td>
ejmListbox</td><td>
ejRangeNavigator</td><td>
ejTreeMap</td></tr>
<tr>
<td>
ejmCheckbox</td><td>
ejLinearGauge</td><td>
ejmRating</td><td>
ejmToggleButton</td></tr>
<tr>
<td>
ejCircularGauge</td><td>
ejMaps</td><td>
ejmRotator</td><td>
ejmToolBar</td></tr>
<tr>
<td>
ejmTextArea</td><td>
ejmTextbox</td><td>
ejmTile</td><td>
</td></tr>
</table>
_ejmAccordion_

<table>
<tr>
<th>
Type</th><th>
Old APIs</th><th>
New APIs</th></tr>
<tr>
<td rowspan = "6">
Members</td><td>
cache</td><td>
enableCache</td></tr>
<tr>
<td>
multipleOpen</td><td>
enableMultipleOpen</td></tr>
<tr>
<td>
persist</td><td>
enablePersistence</td></tr>
<tr>
<td>
heightStyle</td><td>
heightAdjustMode</td></tr>
<tr>
<td>
selectedItemIndex</td><td>
selectedItems</td></tr>
<tr>
<td>
spinner</td><td>
spinnerText</td></tr>
<tr>
<td rowspan = "3">
Methods</td><td>
deselectItem</td><td>
deselectItems</td></tr>
<tr>
<td>
selectItem</td><td>
selectItems</td></tr>
<tr>
<td>
panelCount</td><td>
getItemsCount</td></tr>
<tr>
<td>
Enum</td><td>
heightStyle</td><td>
HeightAdjustMode</td></tr>
</table>
_ejmAutoComplete_

<table>
<tr>
<th>
Type</th><th>
Old APIs</th><th>
New APIs</th></tr>
<tr>
<td rowspan = "10">
Members</td><td>
caseSensitive</td><td>
caseSensitiveSearch</td></tr>
<tr>
<td>
multiValue</td><td>
enableMultiSelect</td></tr>
<tr>
<td>
delimiter</td><td>
delimiterChar</td></tr>
<tr>
<td>
noResults</td><td>
emptyResultText</td></tr>
<tr>
<td>
autoFill</td><td>
enableAutoFill</td></tr>
<tr>
<td>
showCheckbox</td><td>
enableCheckbox</td></tr>
<tr>
<td>
distinct</td><td>
enableDistinct</td></tr>
<tr>
<td>
persist</td><td>
enablePersistence</td></tr>
<tr>
<td>
listSize</td><td>
itemsCount</td></tr>
<tr>
<td>
showNoResults</td><td>
showEmptyResultText</td></tr>
</table>
_ejBarcode_

<table>
<tr>
<th>
Member Type</th><th>
Old API Names</th><th>
New API Names</th><th>
Comments</th></tr>
<tr>
<td>
SymbologyType(Enum)</td><td>
symbologyType</td><td>
SymbologyType</td><td>
</td></tr>
</table>
_ejBulletGraph_

<table>
<tr>
<th>
Member Type</th><th colspan = "3">
Old APIs</th><th colspan = "2">
Old APIs</th><th colspan = "2">
New APIs</th><th>
Comments</th></tr>
<tr>
<td rowspan = "14">
Property</td><td colspan = "3">
comparativeMeasureSymbolStroke comparativeMeasureSymbolStrokeThickness</td><td colspan = "2">
comparativeMeasureSettings.stroke,comparativeMeasureSettings.width</td><td>
comparativeMeasureSymbolStroke, comparativeMeasureSymbolStrokeThicknessproperties are renamed as stroke,width and moved undercomparativeMeasureSettings.</td></tr>
<tr>
<td colspan = "3">
majorTickSizemajorTickStrokemajorTickStrokeThickness</td><td colspan = "2">
majorTickSettings.size, majorTickSettings.stroke,majorTickSettings.width</td><td>
majorTickSize,majorTickStroke,majorTickStrokeThickness properties are renamed as size, stroke, width and moved under majorTickSettings.</td></tr>
<tr>
<td colspan = "3">
minorTickSizeminorTickStrokeminorTickStrokeThickness</td><td colspan = "2">
minorTickSettings.size, minorTickSettings.stroke,minorTickSettings.width</td><td>
minorTickSize, minorTickStroke,majorTickStrokeThickness properties are renamed as size, stroke, width and moved under minorTickSettings.</td></tr>
<tr>
<td colspan = "3">
featuredMeasureBarStrokefeaturedMeasureBarStrokeThickness</td><td colspan = "2">
featuredMeasureSettings.stroke,featuredMeasureSettings.width</td><td>
featuredMeasureBarStroke,featuredMeasureBarStrokeThicknessproperties are renamed as stroke, width and moved under featuredMeasureSettings.</td></tr>
<tr>
<td colspan = "3">
showTooltiptooltipTemplateID</td><td colspan = "2">
tooltip.visible, tooltip.template</td><td>
Tooltip visible property andtemplate property are moved to“tooltip” object.</td></tr>
<tr>
<td colspan = "3">
canResize</td><td colspan = "2">
enableResizing</td><td>
canResize property is renamed toenableResizing.</td></tr>
<tr>
<td colspan = "3">
bindRangeStrokeToLabels</td><td colspan = "2">
applyRangeStrokeToLabels</td><td>
bindRangeStrokeToLabelsproperty is renamed toapplyRangeStrokeToLabels</td></tr>
<tr>
<td colspan = "3">
bindRangeStrokeToTicks</td><td colspan = "2">
applyRangeStrokeToTicks</td><td>
bindRangeStrokeToTicks propertyis renamed toapplyRangeStrokeToTicks.</td></tr>
<tr>
<td colspan = "3">
featureMeasure</td><td colspan = "2">
featureMeasures</td><td>
featureMeasureproperty isrenamed tofeatureMeasures.</td></tr>
<tr>
<td colspan = "3">
caption</td><td colspan = "2">
captionSettings</td><td>
caption property is renamed tocaptionSettings.</td></tr>
<tr>
<td colspan = "3">
caption.subtitle</td><td colspan = "2">
captionSettings.subTitle</td><td>
subtitle in caption is renamed  assubTitle and moved undercaptionSettings.</td></tr>
<tr>
<td colspan = "3">
quantitativeScale</td><td colspan = "2">
quantitativeScaleSettings</td><td>
quantitativeScale is renamed toquantitativeScaleSettings.</td></tr>
<tr>
<td colspan = "3">
quantitativeScale.labels:                           {         labelStroke,        labelSize,        labelOffset        labelPosition   }</td><td colspan = "2">
quantitativeScaleSettings.labelSettings: {      stroke,      size      offset      position }</td><td>
labels in quantitativeScale is renamed to labelSettings and the inner properties are renamed to stroke, size, offset, position.</td></tr>
<tr>
<td colspan = "3">
tooltip</td><td colspan = "2">
tooltipSettings</td><td>
Renamed tooltip property to tooltipSettings.</td></tr>
<tr>
<th>
Member Type</th><th colspan = "2">
Old Enum Names</th><th colspan = "3">
New Enum Names</th><th colspan = "2">
Comments</th></tr>
<tr>
<td rowspan = "7">
Enum</td><td colspan = "2">
ej.BulletGraph.orientation</td><td colspan = "3">
ej.datavisualization.BulletGraph.Orientation</td><td colspan = "2">
</td></tr>
<tr>
<td colspan = "2">
ej.BulletGraph.tickPosition</td><td colspan = "3">
ej.datavisualization.BulletGraph.TickPosition</td><td colspan = "2">
</td></tr>
<tr>
<td colspan = "2">
ej.BulletGraph.labelPosition</td><td colspan = "3">
ej.datavisualization.BulletGraph.LabelPosition</td><td colspan = "2">
</td></tr>
<tr>
<td colspan = "2">
ej.BulletGraph.flowDirection</td><td colspan = "3">
ej.datavisualization.BulletGraph.FlowDirection</td><td colspan = "2">
</td></tr>
<tr>
<td colspan = "2">
ej.BulletGraph.fontStyle</td><td colspan = "3">
ej.datavisualization.BulletGraph.FontStyle</td><td colspan = "2">
</td></tr>
<tr>
<td colspan = "2">
ej.BulletGraph.fontWeight</td><td colspan = "3">
ej.datavisualization.BulletGraph.FontWeight</td><td colspan = "2">
</td></tr>
<tr>
<td colspan = "2">
ej.BulletGraph.themes</td><td colspan = "3">
ej.datavisualization.BulletGraph.Themes</td><td colspan = "2">
</td></tr>
<tr>
<th>
Member Type</th><th>
Event Name</th><th>
Old Argument Names</th><th colspan = "3">
New  Argument Names</th><th colspan = "2">
Comments</th></tr>
<tr>
<td rowspan = "7">
Event</td><td>
drawTicks</td><td>
args.Object</td><td colspan = "3">
args.object</td><td colspan = "2">
Modified the args.Object</td></tr>
<tr>
<td>
drawLabels</td><td>
args.Object</td><td colspan = "3">
args.object</td><td colspan = "2">
Modified the args.Object</td></tr>
<tr>
<td>
drawCaption</td><td>
args.Object</td><td colspan = "3">
args.object</td><td colspan = "2">
Modified the args.Object</td></tr>
<tr>
<td>
drawQualitativeRanges</td><td>
args.Object</td><td colspan = "3">
args.object</td><td colspan = "2">
Modified the args.Object</td></tr>
<tr>
<td>
drawFeatureMeasureBar</td><td>
args.Objectargs.Value</td><td colspan = "3">
args.objectargs.value</td><td colspan = "2">
Modified the args.Object and args.Value</td></tr>
<tr>
<td>
drawCategory</td><td>
args.Objectargs.Value</td><td colspan = "3">
args.objectargs.value</td><td colspan = "2">
Modified the args.Object and args.Value</td></tr>
<tr>
<td>
drawComparativeMeasureSymbol</td><td>
args.Objectargs.Value</td><td colspan = "3">
args.objectargs.value</td><td colspan = "2">
Modified the args.Object and args.Value</td></tr>
<tr>
<td>
</td><td>
</td><td colspan = "2">
</td><td>
</td><td colspan = "2">
</td><td>
</td></tr>
</table>
_ejmButton_

<table>
<tr>
<th>
Type</th><th>
Old APIs</th><th>
New APIs</th></tr>
<tr>
<td rowspan = "5">
Members</td><td>
android.buttonStyle</td><td>
android.style</td></tr>
<tr>
<td>
flat.buttonStyle</td><td>
flat.style</td></tr>
<tr>
<td>
iOS7.buttonStyle</td><td>
iOS7.style</td></tr>
<tr>
<td>
iOS7.buttonColor</td><td>
iOS7.color</td></tr>
<tr>
<td>
windows.buttonStyle</td><td>
windows.style</td></tr>
<tr>
<td rowspan = "3">
Enum</td><td>
android.buttonStyle</td><td>
AndroidStyle</td></tr>
<tr>
<td>
windows.buttonStyle</td><td>
WindowsStyle</td></tr>
<tr>
<td>
flat.buttonStyle</td><td>
FlatStyle</td></tr>
<tr>
<td>
</td><td>
iOS7.buttonStyle</td><td>
iOS7Style</td></tr>
<tr>
<td>
</td><td>
iOS7.buttonColor</td><td>
iOS7Color</td></tr>
</table>
_ejChart_

<table>
<tr>
<th>
Member Type</th><th colspan = "4">
Old APIs</th><th colspan = "2">
New APIs</th><th colspan = "2">
Comments</th></tr>
<tr>
<td rowspan = "14">
Property</td><td colspan = "4">
Localization</td><td colspan = "2">
locale</td><td colspan = "2">
</td></tr>
<tr>
<td colspan = "4">
size.width:100</td><td colspan = "2">
size.width:”100”</td><td>
Width type changed to string from number.</td></tr>
<tr>
<td colspan = "4">
size.height:100</td><td colspan = "2">
size.height:”100”</td><td>
Height type changed to string from number.</td></tr>
<tr>
<td colspan = "4">
commonSeriesOptions.animation:</td><td colspan = "2">
commonSeriesOptions.enableAnimation:</td><td>
</td></tr>
<tr>
<td colspan = "4">
commonSeriesOptions.tooltip.animation:</td><td colspan = "2">
commonSeriesOptions.tooltip.enableAnimation:</td><td>
</td></tr>
<tr>
<td colspan = "4">
series.animation:</td><td colspan = "2">
series.enableAnimation:</td><td>
</td></tr>
<tr>
<td colspan = "4">
series.tooltip.animation:</td><td colspan = "2">
series.tooltip.enableAnimation:</td><td>
</td></tr>
<tr>
<td colspan = "4">
series.dataSource.data:JsonData,series.dataSource.xName:’’,series.dataSource.yName:’’</td><td colspan = "2">
series.dataSource:JsonData,series.xName:’’,series.yName:’’</td><td>
</td></tr>
<tr>
<td colspan = "4">
legend.location.X:10</td><td colspan = "2">
legend.location.x:10</td><td>
</td></tr>
<tr>
<td colspan = "4">
legend.location.Y:10</td><td colspan = "2">
legend.location.y:10</td><td>
</td></tr>
<tr>
<td colspan = "4">
legend.itemSize:</td><td colspan = "2">
legend.itemStyle:</td><td>
</td></tr>
<tr>
<td colspan = "4">
axes.axisName:’’</td><td colspan = "2">
axes.name:’’</td><td>
</td></tr>
<tr>
<td colspan = "4">
primaryXAxis.stripline:’’</td><td colspan = "2">
primaryXAxis.stripLine:’’</td><td>
</td></tr>
<tr>
<td colspan = "4">
primaryXAxis.stripline.zOrder:’’</td><td colspan = "2">
primaryXAxis.stripLine.zIndex:’’</td><td>
</td></tr>
<tr>
<td rowspan = "24">
Enum</td><td colspan = "4">
ej.Chart.crosshairType</td><td colspan = "2">
ej.datavisualization.Chart.CrosshairType</td><td>
</td></tr>
<tr>
<td colspan = "4">
ej.Chart.valuetype</td><td colspan = "2">
ej.datavisualization.Chart.Valuetype</td><td>
</td></tr>
<tr>
<td colspan = "4">
ej.Chart.type</td><td colspan = "2">
ej.datavisualization.Chart.Type</td><td>
</td></tr>
<tr>
<td colspan = "4">
ej.Chart.labelPlacement</td><td colspan = "2">
ej.datavisualization.Chart.LabelPlacement</td><td>
</td></tr>
<tr>
<td colspan = "4">
ej.Chart.labelIntersectAction</td><td colspan = "2">
ej.datavisualization.Chart.LabelIntersectAction</td><td>
</td></tr>
<tr>
<td colspan = "4">
ej.Chart.edgeLabelPlacement</td><td colspan = "2">
ej.datavisualization.Chart.EdgeLabelPlacement</td><td>
</td></tr>
<tr>
<td colspan = "4">
ej.Chart.theme</td><td colspan = "2">
ej.datavisualization.Chart.Theme</td><td>
</td></tr>
<tr>
<td colspan = "4">
ej.Chart.fontWeight</td><td colspan = "2">
ej.datavisualization.Chart.FontWeight</td><td>
</td></tr>
<tr>
<td colspan = "4">
ej.Chart.orientation</td><td colspan = "2">
ej.datavisualization.Chart.Orientation</td><td>
</td></tr>
<tr>
<td colspan = "4">
ej.Chart.fontStyle</td><td colspan = "2">
ej.datavisualization.Chart.FontStyle</td><td>
</td></tr>
<tr>
<td colspan = "4">
ej.Chart.intervalType</td><td colspan = "2">
ej.datavisualization.Chart.IntervalType</td><td>
</td></tr>
<tr>
<td colspan = "4">
ej.Chart.rangePadding</td><td colspan = "2">
ej.datavisualization.Chart.RangePadding</td><td>
</td></tr>
<tr>
<td colspan = "4">
ej.Chart.textAlignment</td><td colspan = "2">
ej.datavisualization.Chart.TextAlignment</td><td>
</td></tr>
<tr>
<td colspan = "4">
ej.Chart.labelPosition</td><td colspan = "2">
ej.datavisualization.Chart.LabelPosition</td><td>
</td></tr>
<tr>
<td colspan = "4">
ej.Chart.zOrder</td><td colspan = "2">
ej.datavisualization.Chart.ZOrder</td><td>
</td></tr>
<tr>
<td colspan = "4">
ej.Chart.unit</td><td colspan = "2">
ej.datavisualization.Chart.Unit</td><td>
</td></tr>
<tr>
<td colspan = "4">
ej.Chart.pyramidMode</td><td colspan = "2">
ej.datavisualization.Chart.PyramidMode</td><td>
</td></tr>
<tr>
<td colspan = "4">
ej.Chart.drawType</td><td colspan = "2">
ej.datavisualization.Chart.DrawType</td><td>
</td></tr>
<tr>
<td colspan = "4">
ej.Chart.shape</td><td colspan = "2">
ej.datavisualization.Chart.Shape</td><td>
</td></tr>
<tr>
<td colspan = "4">
ej.Chart.drawMode</td><td colspan = "2">
ej.datavisualization.Chart.DrawMode</td><td>
</td></tr>
<tr>
<td colspan = "4">
ej.Chart.lineCap</td><td colspan = "2">
ej.datavisualization.Chart.LineCap</td><td>
</td></tr>
<tr>
<td colspan = "4">
ej.Chart.lineJoin</td><td colspan = "2">
ej.datavisualization.Chart.LineJoin</td><td>
</td></tr>
<tr>
<td colspan = "4">
ej.Chart.position</td><td colspan = "2">
ej.datavisualization.Chart.Position</td><td>
</td></tr>
<tr>
<td colspan = "4">
ej.Chart.alignment</td><td colspan = "2">
ej.datavisualization.Chart.Alignment</td><td>
</td></tr>
<tr>
<td colspan = "2">
Member Type</td><td>
Event Names</td><td>
Old Argument Names</td><td colspan = "2">
New Argument Names</td><td colspan = "2">
Comments</td></tr>
<tr>
<td colspan = "2" rowspan = "22">
Event</td><td>
load</td><td>
args:{cancel,CancelDatamodeltype}</td><td colspan = "2">
args:{canceldatamodeltype}</td><td colspan = "2">
args.Cancel is removed.</td></tr>
<tr>
<td>
axesLabelRendering</td><td>
args:{cancelAxisLabelmodeltype}</td><td colspan = "2">
args:{canceldatamodeltype}</td><td colspan = "2">
args.data is added.args.Cancel is removed.args.Axis, args.Label is removed.</td></tr>
<tr>
<td>
axesRangeCalculate</td><td>
args:{cancelCancelDatamodeltype}</td><td colspan = "2">
args:{canceldatamodeltype}</td><td colspan = "2">
args.data is added.args.Cancel is removed.</td></tr>
<tr>
<td>
axesTitleRendering</td><td>
args:{cancelCancelData={Axes, Location, Title}modeltype}</td><td colspan = "2">
args:{canceldata={axes, location, title}modeltype}</td><td colspan = "2">
Modified the args.Dataargs.Cancel is removed.</td></tr>
<tr>
<td>
chartAreaBoundsCalculate</td><td>
args:{cancelCancelData={AreaBound}modeltype}</td><td colspan = "2">
args:{canceldata={areaBounds}modeltype}</td><td colspan = "2">
Modified the args.Dataargs.Cancel is removed.</td></tr>
<tr>
<td>
legendItemRendering</td><td>
args:{cancelCancelData={Legend, LegendItem, Location, Style, SymbolShape}modeltype}</td><td colspan = "2">
args:{canceldata={legend, legendItem, location, style, symbolShape}modeltype}</td><td colspan = "2">
Modified the args.Dataargs.Cancel is removed.</td></tr>
<tr>
<td>
legendBoundsCalculate</td><td>
args:{cancelCancelData={LegendBound }modeltype}</td><td colspan = "2">
args:{canceldata={legendBounds }modeltype}</td><td colspan = "2">
Modified the args.Dataargs.Cancel is removed.</td></tr>
<tr>
<td>
preRender</td><td>
args:{cancelCancelDatamodeltype}</td><td colspan = "2">
args:{canceldatamodeltype}</td><td colspan = "2">
Modified the args.Dataargs.Cancel is removed.</td></tr>
<tr>
<td>
seriesRendering</td><td>
args:{cancelCancelDatamodeltype}</td><td colspan = "2">
args:{canceldatamodeltype}</td><td colspan = "2">
Modified the args.Dataargs.Cancel is removed.</td></tr>
<tr>
<td>
symbolRendering</td><td>
args:{cancelCancelData={Location,Style}modeltype}</td><td colspan = "2">
args:{canceldata={location, style}modeltype}</td><td colspan = "2">
Modified the args.Dataargs.Cancel is removed.</td></tr>
<tr>
<td>
titleRendering</td><td>
args:{cancelCancelData={Location,Size, Title}modeltype}</td><td colspan = "2">
args:{canceldata={Location, Size, Title}modeltype}</td><td colspan = "2">
Modified the args.Dataargs.Cancel is removed.</td></tr>
<tr>
<td>
axesLabelsInitialize</td><td>
args:{cancelCancelData={Axes}modeltype}</td><td colspan = "2">
args:{canceldata={axes}modeltype}</td><td colspan = "2">
Modified the args.Dataargs.Cancel is removed.</td></tr>
<tr>
<td>
pointRegionClick</td><td>
args:{cancelCancelData={Region}modeltype}</td><td colspan = "2">
args:{canceldata={region}modeltype}</td><td colspan = "2">
Modified the args.Dataargs.Cancel is removed</td></tr>
<tr>
<td>
pointRegionMouseMove</td><td>
args:{cancelCancelData={Region}modeltype}</td><td colspan = "2">
args:{canceldata={region}modeltype}</td><td colspan = "2">
Modified the args.Dataargs.Cancel is removed.</td></tr>
<tr>
<td>
legendItemClick</td><td>
args:{cancelCancelData={LegendItem, Series}modeltype}</td><td colspan = "2">
args:{canceldata={legendItem, series}modeltype}</td><td colspan = "2">
Modified the args.Dataargs.Cancel is removed.</td></tr>
<tr>
<td>
legendItemMouseMove</td><td>
args:{cancelCancelData={LegendItem, Series}modeltype}</td><td colspan = "2">
args:{canceldata={legendItem, series}modeltype}</td><td colspan = "2">
Modified the args.Dataargs.Cancel is removed.</td></tr>
<tr>
<td>
displayTextRendering</td><td>
args:{cancelCancelData={Location, PointIndex,  SeriesIndex, Text}model }</td><td colspan = "2">
args:{canceldata={location,pointIndex, seriesIndex, text}model}</td><td colspan = "2">
Modified the args.Dataargs.Cancel is removed.</td></tr>
<tr>
<td>
toolTipInitialize</td><td>
args:{cancelCancelDatamodeltype}</td><td colspan = "2">
args:{canceldatamodeltype}</td><td colspan = "2">
Modified the args.Dataargs.Cancel is removed.</td></tr>
<tr>
<td>
trackAxisToolTip</td><td>
args:{cancelCancelDatamodeltype}</td><td colspan = "2">
args:{canceldatamodeltype}</td><td colspan = "2">
Modified the args.Dataargs.Cancel is removed.</td></tr>
<tr>
<td>
trackToolTip</td><td>
args:{cancelCancelDatamodeltype}</td><td colspan = "2">
args:{cancelDatamodeltype}</td><td colspan = "2">
Modified the args.Dataargs.Cancel is removed.</td></tr>
<tr>
<td>
animationComplete</td><td>
args:{cancelCancelData={Series}modeltype}</td><td colspan = "2">
args:{canceldata={series}modeltype}</td><td colspan = "2">
Modified the args.Dataargs.Cancel is removed.</td></tr>
<tr>
<td>
loaded</td><td>
args:{cancelCancelData={Model}modeltype}</td><td colspan = "2">
args:{canceldata={model}modeltype}</td><td colspan = "2">
Modified the args.Dataargs.Cancel is removed.</td></tr>
</table>
_ejmCheckbox_

<table>
<tr>
<th>
Type</th><th>
Old APIs</th><th>
New APIs</th></tr>
<tr>
<td rowspan = "3">
Members</td><td>
check</td><td>
checked</td></tr>
<tr>
<td>
indeterminateState</td><td>
enableTriState</td></tr>
<tr>
<td>
indeterminate</td><td>
checkState</td></tr>
</table>
_ejCircularGauge_

<table>
<tr>
<th>
Member Type</th><th>
Old APIs</th><th>
New APIs</th><th>
Comments</th></tr>
<tr>
<td rowspan = "50">
Property</td><td>
frameType</td><td rowspan = "4">
frame: {frameType: "fullCircle",                   backgroundImageUrl: null,             halfCircleFrameStartAngle: 180,                halfCircleFrameEndAngle: 360},</td><td rowspan = "4">
All frame properties are moved to Object type.</td></tr>
<tr>
<td>
halfCircleFrameStartAngle</td></tr>
<tr>
<td>
halfCircleFrameEndAngle</td></tr>
<tr>
<td>
backgroundImageUrl</td></tr>
<tr>
<td>
canResize</td><td>
enableResize</td><td>
</td></tr>
<tr>
<td>
animate</td><td>
enableAnimation</td><td>
</td></tr>
<tr>
<td>
capBorderColor</td><td rowspan = "5">
pointerCap: {    radius: 7,    borderWidth: 3,    interiorGradient: null,    borderColor: null,    backgroundColor: null,}</td><td rowspan = "5">
All pointer cap properties are moved to Object type.</td></tr>
<tr>
<td>
capBackgroundColor</td></tr>
<tr>
<td>
pointerCapRadius</td></tr>
<tr>
<td>
pointerCapBorderWidth</td></tr>
<tr>
<td>
capInteriorGradient</td></tr>
<tr>
<td>
borderColor</td><td rowspan = "2">
border:{   color: null,   width:3}</td><td rowspan = "2">
All border properties are moved to Object type.</td></tr>
<tr>
<td>
scaleBorderWidth</td></tr>
<tr>
<td>
scaleBarSize</td><td>
size</td><td>
</td></tr>
<tr>
<td>
scaleRadius</td><td>
radius</td><td>
</td></tr>
<tr>
<td>
scaleDirection</td><td>
direction</td><td>
</td></tr>
<tr>
<td>
labelAutoAngle</td><td>
labels.autoAngle</td><td>
This property is moved under the label collection.</td></tr>
<tr>
<td>
pointerLength</td><td>
length</td><td>
</td></tr>
<tr>
<td>
pointerPosition</td><td>
placement</td><td>
</td></tr>
<tr>
<td>
pointerWidth</td><td>
width</td><td>
</td></tr>
<tr>
<td>
pointerGradient</td><td>
gradients</td><td>
</td></tr>
<tr>
<td>
pointerType</td><td>
type</td><td>
</td></tr>
<tr>
<td>
borderColor</td><td rowspan = "2">
border:{   color: null,   width:3}</td><td rowspan = "2">
All border properties are moved to Object type.</td></tr>
<tr>
<td>
borderWidth</td></tr>
<tr>
<td>
rangePosition</td><td>
placement</td><td>
</td></tr>
<tr>
<td>
rangeGradient</td><td>
gradients</td><td>
</td></tr>
<tr>
<td>
borderColor</td><td rowspan = "2">
border:{   color: null,   width:3}</td><td rowspan = "2">
All border properties are moved to Object type.</td></tr>
<tr>
<td>
borderWidth</td></tr>
<tr>
<td>
tickColor</td><td>
color</td><td>
</td></tr>
<tr>
<td>
tickStyle</td><td>
type</td><td>
</td></tr>
<tr>
<td>
tickPosition</td><td>
placement</td><td>
</td></tr>
<tr>
<td>
tickHeight</td><td>
height</td><td>
</td></tr>
<tr>
<td>
tickWidth</td><td>
width</td><td>
</td></tr>
<tr>
<td>
labelColor</td><td>
color</td><td>
</td></tr>
<tr>
<td>
labelPosition</td><td>
placement</td><td>
</td></tr>
<tr>
<td>
labelStyle</td><td>
type</td><td>
</td></tr>
<tr>
<td>
scales.labelAutoAngle</td><td>
autoAngle</td><td>
</td></tr>
<tr>
<td>
indicatorHeight</td><td>
height</td><td>
</td></tr>
<tr>
<td>
indicatorWidth</td><td>
width</td><td>
</td></tr>
<tr>
<td>
indicatorStyle</td><td>
type</td><td>
</td></tr>
<tr>
<td>
indicatorValue</td><td>
value</td><td>
</td></tr>
<tr>
<td>
indicatorLocation</td><td>
position</td><td>
</td></tr>
<tr>
<td>
subGaugeHeight</td><td>
height</td><td>
</td></tr>
<tr>
<td>
subGaugeWidth</td><td>
width</td><td>
</td></tr>
<tr>
<td>
location</td><td>
position</td><td>
</td></tr>
<tr>
<td>
labelColor</td><td>
color</td><td>
</td></tr>
<tr>
<td>
labelValue</td><td>
value</td><td>
</td></tr>
<tr>
<td>
location</td><td>
position</td><td>
</td></tr>
<tr>
<td>
customLabel</td><td>
customLabels</td><td>
</td></tr>
<tr>
<td>
gradient</td><td>
gradients</td><td>
</td></tr>
<tr>
<td rowspan = "12">
Enum</td><td>
ej.CircularGauge.direction = {Clockwise: "Clockwise",CounterClockwise:"CounterClockwise"    };</td><td>
ej.CircularGauge.Directions = {Clockwise: "clockwise",CounterClockwise: "counterclockwise"    };</td><td>
</td></tr>
<tr>
<td>
ej.CircularGauge.pointerPlacement = {Near: "Near",Far: "Far",Center: "Center"    };</td><td>
ej.CircularGauge.PointerPlacement = {Near: "near",Far: "far",Center: "center"    };</td><td>
</td></tr>
<tr>
<td>
ej.CircularGauge.pointerType = {Needle: "Needle",Marker: "Marker"    };</td><td>
ej.CircularGauge.PointerType = {Needle: "needle",Marker: "marker"    };</td><td>
</td></tr>
<tr>
<td>
ej.CircularGauge.needleType = {Triangle: "Triangle",Rectangle: "Rectangle",Trapezoid: "Trapezoid",Arrow: "Arrow"    };</td><td>
ej.CircularGauge.NeedleType = {Triangle: "triangle",Rectangle: "rectangle",Trapezoid: "trapezoid",Arrow: "arrow"    };</td><td>
</td></tr>
<tr>
<td>
ej.CircularGauge.markerType = {Rectangle: "Rectangle",Triangle: "Triangle",Ellipse: "Ellipse",Diamond: "Diamond",Pentagon: "Pentagon",Circle: "Circle",Slider: "Slider",Pointer: "Pointer",Wedge: "Wedge",Trapezoid: "Trapezoid",RoundedRectangle:"RoundedRectangle"    };</td><td>
ej.CircularGauge.MarkerType = {Rectangle: "rectangle",Triangle: "triangle",Ellipse: "ellipse",Diamond: "diamond",Pentagon: "pentagon",Circle: "circle",Slider: "slider",Pointer: "pointer",Wedge: "wedge",Trapezoid: "trapezoid",RoundedRectangle: "roundedrectangle"    };</td><td>
</td></tr>
<tr>
<td>
ej.CircularGauge.rangePlacement = {Near: "Near",Far: "Far",Center: "Center"    };</td><td>
ej.CircularGauge.RangePlacement = {Near: "near",Far: "far",Center: "center"    };</td><td>
</td></tr>
<tr>
<td>
ej.CircularGauge.tickType = {Major: "Major",Minor: "Minor"    };</td><td>
ej.CircularGauge.TickType = {Major: "major",Minor: "minor"    };</td><td>
</td></tr>
<tr>
<td>
ej.CircularGauge.tickPlacement = {Near: "Near",Far: "Far",Center: "Center"    };</td><td>
ej.CircularGauge.TickPlacement = {Near: "near",Far: "far",Center: "center"    };</td><td>
</td></tr>
<tr>
<td>
ej.CircularGauge.labelPlacement = {Near: "Near",Far: "Far",Center: "Center"    };</td><td>
ej.CircularGauge.LabelPlacement = {Near: "near",Far: "far",Center: "center"    };</td><td>
</td></tr>
<tr>
<td>
ej.CircularGauge.labelType = {Major: "Major",Minor: "Minor"    };</td><td>
ej.CircularGauge.LabelType = {Major: "major",Minor: "minor"    };</td><td>
</td></tr>
<tr>
<td>
ej.CircularGauge.unitTextPlacement = {Back: "Back",Front: "Front"    };</td><td>
ej.CircularGauge.UnitTextPlacement = {Back: "back",Front: "front"    };</td><td>
</td></tr>
<tr>
<td>
ej.CircularGauge.indicatorType = {Rectangle: "Rectangle",Circle: "Circle",RoundedRectangle:"RoundedRectangle",Text: "Text"    };</td><td>
ej.CircularGauge.IndicatorType = {Rectangle: "rectangle",Circle: "circle",RoundedRectangle:"roundedrectangle",Text: "text"    };</td><td>
</td></tr>
<tr>
<td rowspan = "19">
Events arguments</td><td>
args.location</td><td>
args.position</td><td>
For Ticks.</td></tr>
<tr>
<td>
args.tickAngle</td><td rowspan = "3">
args.tick{angleelementIndex}</td><td rowspan = "3">
arguments are moved to Object type.</td></tr>
<tr>
<td>
args.tickElement</td></tr>
<tr>
<td>
args.tickIndex</td></tr>
<tr>
<td>
args.tickValue</td><td>
args.pointervalue</td><td>
</td></tr>
<tr>
<td>
args.location</td><td>
args.position</td><td>
</td></tr>
<tr>
<td>
args.labelAngle</td><td rowspan = "3">
args.label{angleelementIndex}</td><td rowspan = "3">
arguments are moved to Object type.</td></tr>
<tr>
<td>
args.labelElement</td></tr>
<tr>
<td>
args.labelIndex</td></tr>
<tr>
<td>
args.labelValue</td><td>
args.pointerValue</td><td>
</td></tr>
<tr>
<td>
args.location</td><td>
args.position</td><td>
For labels.</td></tr>
<tr>
<td>
args.pointerAngle</td><td rowspan = "3">
args.pointer{angleelementIndex}</td><td rowspan = "3">
Arguments are moved to Object type.</td></tr>
<tr>
<td>
args.pointerElement</td></tr>
<tr>
<td>
args.pointerIndex</td></tr>
<tr>
<td>
args.location</td><td>
args.position</td><td>
For range.</td></tr>
<tr>
<td>
args.location</td><td>
args.position</td><td>
For Customlabels.</td></tr>
<tr>
<td>
args.location</td><td>
args.position</td><td>
For indicator.</td></tr>
<tr>
<td>
args.location</td><td>
args.position</td><td>
For pointer cap.</td></tr>
<tr>
<td>
args.pointerElement</td><td>
args.pointer{angleelementvalueIndex}</td><td>
arguments are moved to Object type.</td></tr>
</table>
_ejmDatePicker_

<table>
<tr>
<th>
Type</th><th>
Old APIs</th><th>
New APIs</th></tr>
<tr>
<td rowspan = "2">
Members</td><td>
localize</td><td>
culture</td></tr>
<tr>
<td>
defaultDate</td><td>
value</td></tr>
</table>
_ejmDialog_

<table>
<tr>
<th>
Type</th><th>
Old APIs</th><th>
New APIs</th></tr>
<tr>
<td rowspan = "6">
Members</td><td>
autoOpen</td><td>ru
enableAutoOpen</td></tr>
<tr>
<td>
showButton</td><td>
showButtons</td></tr>
<tr>
<td>
modal</td><td>
enableModal</td></tr>
<tr>
<td>
nativeScroll</td><td>
enableNativeScrolling</td></tr>
<tr>
<td>
dialogMode</td><td>
mode</td></tr>
<tr>
<td>
template</td><td>
templateId</td></tr>
<tr>
<td>
Enum</td><td>
dialogMode</td><td>
Mode</td></tr>
</table>
_ejDigitalGauge_

<table>
<tr>
<th>
Member Type </th><th>
Old API Names</th><th>
New API Names</th><th>
Comments </th></tr>
<tr>
<td rowspan = "9">
Property</td><td>
frameBackgroundImageUrl</td><td rowspan = "3">
frame: {     backgroundImageUrl:null,     outerWidth: 12,     innerWidth: 8, },</td><td rowspan = "3">
All properties are moved to Object type.</td></tr>
<tr>
<td>
frameOuterWidth</td></tr>
<tr>
<td>
frameInnerWidth</td></tr>
<tr>
<td>
segmentLength</td><td rowspan = "5">
segmentSettings:{      color:null,      length:2,      opacity:1,      spacing:2,      width:3,    }</td><td rowspan = "5">
</td></tr>
<tr>
<td>
segmentOpacity</td></tr>
<tr>
<td>
segmentSpacing</td></tr>
<tr>
<td>
segmentWidth</td></tr>
<tr>
<td>
segmentColor</td></tr>
<tr>
<td>
canResize</td><td>
enableResize</td><td>
</td></tr>
<tr>
<td>
Enum</td><td>
ej.characterType = {SevenSegment:"SevenSegment",FourteenSegment:"FourteenSegment",SixteenSegment:"SixteenSegment",EightCrossEightDotMatrix:"EightCrossEightDotMatrix",EightCrossEightSquareMatrix:"EightCrossEightSquareMatrix"    };</td><td>
ej.CharacterType = {SevenSegment:"sevensegment",FourteenSegment:"fourteensegment",SixteenSegment:"sixteensegment",EightCrossEightDotMatrix:"eightcrosseightdotmatrix",EightCrossEightSquareMatrix:"eightcrosseightsquarematrix"    };</td><td>
</td></tr>
<tr>
<td>
Enum</td><td>
ej.textAlignment = {Left: "Left",Right: "Right"    };</td><td>
ej.TextAlignment = {Left: "left",Right: "right"    };</td><td>
</td></tr>
<tr>
<td>
Enum</td><td>
ej.fontStyle = {Normal: "Normal",Bold: "Bold",Italic: "Italic",Underline: "Underline",Strikeout: "Strikeout"    };</td><td>
ej.FontStyle = {Normal: "normal",Bold: "bold",Italic: "italic",Underline: "underline",Strikeout: "strikeout"    };</td><td>
</td></tr>
</table>
_ejmGrid_

<table>
<tr>
<th>
Type</th><th>
Old APIs</th><th>
New APIs</th></tr>
<tr>
<td rowspan = "6">
Members</td><td>
persist </td><td>
enablePersistence</td></tr>
<tr>
<td>
scrollSettings.allowHorizontalScrolling </td><td>
scrollSettings.enableRowScrolling</td></tr>
<tr>
<td>
scrollSettings.allowVerticalScrolling </td><td>
scrollSettings.enableColumnScrolling</td></tr>
<tr>
<td>
scrollSettings.nativeScrolling</td><td>
scrollSettings.enableNativeScrolling </td></tr>
<tr>
<td>
selectedRow </td><td>
selectedRowIndex</td></tr>
<tr>
<td>
showColumnSelector</td><td>
allowColumnSelector</td></tr>
<tr>
<td>
Methods</td><td>
sendRefreshRequest   </td><td>
refreshContent</td></tr>
<tr>
<td rowspan = "3">
Enum</td><td>
pagerDisplay</td><td>
PagerDisplay</td></tr>
<tr>
<td>
pagerType</td><td>
PagerType</td></tr>
<tr>
<td>
filterBarMode</td><td>
FilterBarMode</td></tr>
</table>
_ejmHeader_

<table>
<tr>
<th>
Type</th><th>
Old APIs</th><th>
New APIs</th></tr>
<tr>
<td>
Members</td><td>
windows.customText </td><td>
windows.enableCustomText</td></tr>
</table>
_ejmListbox_

<table>
<tr>
<th>
Type</th><th>
Old APIs</th><th>
New APIs</th></tr>
<tr>
<td rowspan = "32">
Members</td><td>
ajaxOptions</td><td>
ajaxSettings </td></tr>
<tr>
<td>
cache</td><td>
enableCache</td></tr>
<tr>
<td>
autoScrollHeight</td><td>
autoAdjustScrollHeight </td></tr>
<tr>
<td>
autoHeight </td><td>
autoAdjustHeight</td></tr>
<tr>
<td>
loadAjaxContent</td><td>
enableAjax</td></tr>
<tr>
<td>
groupList </td><td>
enableGroupList</td></tr>
<tr>
<td>
nativeScroll </td><td>
enableNativeScrolling</td></tr>
<tr>
<td>
fields.NavigateUrl</td><td>
fieldSettings.navigateUrl</td></tr>
<tr>
<td>
fields.Href</td><td>
fieldSettings.href</td></tr>
<tr>
<td>
fields.LoadAjaxContent</td><td>
fieldSettings.enableAjax</td></tr>
<tr>
<td>
fields.PreventSelection</td><td>
fieldSettings.preventSelection</td></tr>
<tr>
<td>
fields.PersistSelection</td><td>
fieldSettings.persistSelection</td></tr>
<tr>
<td>
fields.Text</td><td>
fieldSettings.text</td></tr>
<tr>
<td>
fields.EnableCheckMark</td><td>
fieldSettings.enableCheckMark</td></tr>
<tr>
<td>
fields.Checked</td><td>
fieldSettings.checked</td></tr>
<tr>
<td>
fields.PrimaryKey </td><td>
fieldSettings.primaryKey</td></tr>
<tr>
<td>
fields.ParentPrimaryKey </td><td>
fieldSettings.parentPrimaryKey</td></tr>
<tr>
<td>
fields.ImageClass</td><td>
fieldSettings.imageClass</td></tr>
<tr>
<td>
fields.ImageUrl</td><td>
fieldSettings.imageUrl</td></tr>
<tr>
<td>
fields.ChildTitle</td><td>
fieldSettings.childHeaderTitle</td></tr>
<tr>
<td>
fields.ChildId </td><td>
fieldSettings.childId</td></tr>
<tr>
<td>
fields.ChildButtonText </td><td>
fieldSettings.childHeaderBackButtonText</td></tr>
<tr>
<td>
fields.RenderTemplate</td><td>
fieldSettings.renderTemplate</td></tr>
<tr>
<td>
fields.TemplateId </td><td>
fieldSettings.templateId</td></tr>
<tr>
<td>
fields.TouchStart </td><td>
fieldSettings.touchStart</td></tr>
<tr>
<td>
fields.TouchEnd </td><td>
fieldSettings.touchEnd</td></tr>
<tr>
<td>
fields.Attributes</td><td>
fieldSettings.attributes</td></tr>
<tr>
<td>
headerBackText</td><td>
headerBackButtonText </td></tr>
<tr>
<td>
headerBack</td><td>
showHeaderBackButton </td></tr>
<tr>
<td>
scrollbars</td><td>
showScrollbars </td></tr>
<tr>
<td>
windows->preventSkewing</td><td>
windows ->preventSkew</td></tr>
<tr>
<td>
headerHideForUnSupportedDevice</td><td>
hideHeaderForUnsupportedDevice</td></tr>
<tr>
<td rowspan = "19">
Methods</td><td>
addListItem</td><td>
addItem </td></tr>
<tr>
<td>
checkAllListItem </td><td>
checkAllItem</td></tr>
<tr>
<td>
checkListItem</td><td>
checkItem </td></tr>
<tr>
<td>
disableListItem </td><td>
disableItem</td></tr>
<tr>
<td>
enableListItem </td><td>
enableItem</td></tr>
<tr>
<td>
getActiveListItem </td><td>
getActiveItem</td></tr>
<tr>
<td>
getActiveListItemText </td><td>
getActiveItemText</td></tr>
<tr>
<td>
getCheckedListItems </td><td>
getCheckedItems</td></tr>
<tr>
<td>
getCheckedListItemsText </td><td>
getCheckedItemsText</td></tr>
<tr>
<td>
getListItemCount </td><td>
getItemsCount</td></tr>
<tr>
<td>
getListItemText </td><td>
getItemText</td></tr>
<tr>
<td>
hideList</td><td>
hide </td></tr>
<tr>
<td>
showList</td><td>
show</td></tr>
<tr>
<td>
hideListItem</td><td>
hideItem</td></tr>
<tr>
<td>
showListItem</td><td>
showItem</td></tr>
<tr>
<td>
removeListItem </td><td>
removeItem</td></tr>
<tr>
<td>
selectListItem</td><td>
selectItem </td></tr>
<tr>
<td>
unCheckAllListItem</td><td>
unCheckAllItem </td></tr>
<tr>
<td>
unCheckListItem</td><td>
unCheckItem </td></tr>
<tr>
<td rowspan = "5">
Events</td><td>
ajaxBeforeSend</td><td>
ajaxBeforeLoad </td></tr>
<tr>
<td>
ajaxLoadComplete </td><td>
ajaxComplete</td></tr>
<tr>
<td>
ajaxLoadError </td><td>
ajaxError</td></tr>
<tr>
<td>
ajaxLoadSuccess </td><td>
ajaxSuccess</td></tr>
<tr>
<td>
headerButtonTap</td><td>
headerBackButtonTap </td></tr>
</table>
_ejLinearGauge_

<table>
<tr>
<th>
Member Type</th><th>
Old API Names</th><th>
New API Names</th><th>
Comments</th></tr>
<tr>
<td rowspan = "44">
Property</td><td>
frameBackgroundImageUrl</td><td rowspan = "3">
frame: {     backgroundImageUrl:null,     outerWidth: 12,     innerWidth: 8, },</td><td rowspan = "3">
Properties are moved to Object type.</td></tr>
<tr>
<td>
frameOuterWidth</td></tr>
<tr>
<td>
frameInnerWidth</td></tr>
<tr>
<td>
canResize</td><td>
enableResize</td><td>
</td></tr>
<tr>
<td>
animate</td><td>
enableAnimation</td><td>
</td></tr>
<tr>
<td>
scaleBarSize</td><td>
width</td><td>
</td></tr>
<tr>
<td>
scaleDirection</td><td>
direction</td><td>
</td></tr>
<tr>
<td>
scaleBarLength</td><td>
length</td><td>
</td></tr>
<tr>
<td>
scaleStyle</td><td>
type</td><td>
</td></tr>
<tr>
<td>
location</td><td>
position</td><td>
</td></tr>
<tr>
<td>
borderColor</td><td rowspan = "2">
border:{   color: null,   width:3}</td><td rowspan = "2">
Border properties are moved to object type.</td></tr>
<tr>
<td>
borderWidth</td></tr>
<tr>
<td>
tickColor</td><td>
color</td><td>
</td></tr>
<tr>
<td>
tickStyle</td><td>
type</td><td>
</td></tr>
<tr>
<td>
tickPlacement</td><td>
placement</td><td>
</td></tr>
<tr>
<td>
tickHeight</td><td>
height</td><td>
</td></tr>
<tr>
<td>
tickWidth</td><td>
width</td><td>
</td></tr>
<tr>
<td>
xDistanceFromScale</td><td rowspan = "2">
distanceFromScale: { x: 50, y: 50 }</td><td rowspan = "2">
Property is moved to object type.</td></tr>
<tr>
<td>
yDistanceFromScale</td></tr>
<tr>
<td>
rangePosition</td><td>
placement</td><td>
</td></tr>
<tr>
<td>
rangeGradient</td><td>
gradients</td><td>
</td></tr>
<tr>
<td>
borderColor</td><td rowspan = "2">
border:{   color: null,   width:3}</td><td rowspan = "2">
Property is moved to object type.</td></tr>
<tr>
<td>
borderWidth</td></tr>
<tr>
<td>
labelStyle</td><td>
type</td><td>
</td></tr>
<tr>
<td>
labelPlacement</td><td>
placement</td><td>
</td></tr>
<tr>
<td>
unitTextPosition</td><td>
unitTextPlacement</td><td>
</td></tr>
<tr>
<td>
xDistanceFromScale</td><td rowspan = "2">
distanceFromScale: { x: 50, y: 50 }</td><td rowspan = "2">
Property is moved to object type.</td></tr>
<tr>
<td>
yDistanceFromScale</td></tr>
<tr>
<td>
pointerLength</td><td>
length</td><td>
</td></tr>
<tr>
<td>
pointerPlacement</td><td>
placement</td><td>
</td></tr>
<tr>
<td>
pointerGradient</td><td>
gradients</td><td>
</td></tr>
<tr>
<td>
pointerWidth</td><td>
width</td><td>
</td></tr>
<tr>
<td>
markerStyle</td><td>
type</td><td>
</td></tr>
<tr>
<td>
pointerWidth</td><td>
width</td><td>
</td></tr>
<tr>
<td>
scaleBarGradient</td><td>
gradients</td><td>
</td></tr>
<tr>
<td>
indicatorHeight</td><td>
height</td><td>
</td></tr>
<tr>
<td>
indicatorStyle</td><td>
type</td><td>
</td></tr>
<tr>
<td>
indicatorWidth</td><td>
width</td><td>
</td></tr>
<tr>
<td>
location</td><td>
position</td><td>
</td></tr>
<tr>
<td>
labelColor</td><td>
color</td><td>
</td></tr>
<tr>
<td>
labelValue</td><td>
value</td><td>
</td></tr>
<tr>
<td>
Location</td><td>
position</td><td>
</td></tr>
<tr>
<td>
customLabel</td><td>
customLabels</td><td>
</td></tr>
<tr>
<td>
gradient</td><td>
gradients</td><td>
</td></tr>
<tr>
<td rowspan = "12">
Enum</td><td>
ej.tickType = {MajorInterval: "MajorInterval",MinorInterval: "MinorInterval"    };</td><td>
ej.TickType = {MajorInterval: "majorinterval",MinorInterval: "minorinterval"    };</td><td>
</td></tr>
<tr>
<td>
ej.labelType = {Major: "Major",Minor: "Minor"    };</td><td>
ej.LabelType = {Major: "major",Minor: "minor"    };</td><td>
</td></tr>
<tr>
<td>
ej.fontType = {Bold: "Bold",Italic: "Italic",Regular: "Regular",Strikeout: "Strikeout",Underline: "Underline"    };</td><td>
ej.FontStyle = {Bold: "bold",Italic: "italic",Regular: "regular",Strikeout: "strikeout",Underline: "underline"    };</td><td>
</td></tr>
<tr>
<td>
ej.pointerPlacement = {Near: "Near",Far: "Far",Center: "Center"    };</td><td>
ej.PointerPlacement = {Near: "near",Far: "far",Center: "center"    };</td><td>
</td></tr>
<tr>
<td>
ej.tickPlacement = {Near: "Near",Far: "Far",Center: "Center"    };</td><td>
ej.TickPlacement = {Near: "near",Far: "far",Center: "center"};</td><td>
</td></tr>
<tr>
<td>
ej.labelPlacement = {Near: "Near",Far: "Far",Center: "Center"    };</td><td>
ej.LabelPlacement = {Near: "near",Far: "far",Center: "center"    };</td><td>
</td></tr>
<tr>
<td>
ej.rangePlacement = {Near: "Near",Far: "Far",Center: "Center"    };</td><td>
ej.RangePlacement = {Near: "near",Far: "far",Center: "center"    };</td><td>
</td></tr>
<tr>
<td>
ej.unitTextPlacement = {Front: "Front",Back: "Back"    };</td><td>
ej.UnitTextPlacement = {Front: "front",Back: "back"    };</td><td>
</td></tr>
<tr>
<td>
ej.direction = {Clockwise: "Clockwise",CounterClockwise:"CounterClockwise"    };</td><td>
ej.Directions = {Clockwise: "clockwise",CounterClockwise:"counterclockwise"    };</td><td>
</td></tr>
<tr>
<td>
ej.scaleType = {Rectangle: "Rectangle",RoundedRectangle:"RoundedRectangle",Thermometer: "Thermometer"    };</td><td>
ej.ScaleType = {Rectangle: "rectangle",RoundedRectangle:"roundedrectangle",Thermometer: "thermometer"    };</td><td>
</td></tr>
<tr>
<td>
ej.indicatorType = {Rectangle: "Rectangle",Circle: "Circle",RoundedRectangle:"RoundedRectangle",Text: "Text"    };</td><td>
ej.IndicatorType = {Rectangle: "rectangle",Circle: "circle",RoundedRectangle:"roundedrectangle",Text: "text"    };</td><td>
</td></tr>
<tr>
<td>
ej.markerType = {Rectangle: "Rectangle",Triangle: "Triangle",Ellipse: "Ellipse",Diamond: "Diamond",Pentagon: "Pentagon",Circle: "Circle",Star: "Star",Slider: "Slider",Pointer: "Pointer",Wedge: "Wedge",Trapezoid: "Trapezoid",RoundedRectangle:"RoundedRectangle"    };</td><td>
ej.MarkerType = {Rectangle: "rectangle",Triangle: "triangle",Ellipse: "ellipse",Diamond: "diamond",Pentagon: "pentagon",Circle: "circle",Star: "star",Slider: "slider",Pointer: "pointer",Wedge: "wedge",Trapezoid: "trapezoid",RoundedRectangle:"roundedrectangle"    };</td><td>
</td></tr>
<tr>
<td rowspan = "20">
Event Argument</td><td>
args.location</td><td>
args.position</td><td>
For ticks.</td></tr>
<tr>
<td>
args.tickAngle</td><td rowspan = "4">
args.tick{angle,element,index,value}</td><td rowspan = "4">
arguments are moved to Object type.</td></tr>
<tr>
<td>
args.tickElement</td></tr>
<tr>
<td>
args.tickIndex</td></tr>
<tr>
<td>
args.tickValue</td></tr>
<tr>
<td>
args.location</td><td>
args.position</td><td>
For label.</td></tr>
<tr>
<td>
args.labelAngle</td><td rowspan = "4">
args.tick{angle,element,index,value}</td><td rowspan = "4">
arguments are moved to Object type.</td></tr>
<tr>
<td>
args.labelElement</td></tr>
<tr>
<td>
args.labelIndex</td></tr>
<tr>
<td>
args.labelValue</td></tr>
<tr>
<td>
args.location</td><td>
args.position</td><td>
For Bar pointer.</td></tr>
<tr>
<td>
args.location</td><td>
args.position</td><td>
For Marker pointer.</td></tr>
<tr>
<td>
args.location</td><td>
args.position</td><td>
For Custom Label.</td></tr>
<tr>
<td>
args.location</td><td>
args.position</td><td>
For Range.</td></tr>
<tr>
<td>
args.location</td><td>
args.position</td><td>
For Indicator.</td></tr>
<tr>
<td>
args.location</td><td>
args.position</td><td>
For Render Complete.</td></tr>
<tr>
<td>
args.pointerElement</td><td rowspan = "4">
args.pointer{angleelementIndexvalue}</td><td rowspan = "4">
arguments are moved to Object type.</td></tr>
<tr>
<td>
args.pointerIndex</td></tr>
<tr>
<td>
args.pointerValue</td></tr>
<tr>
<td>
args.pointerAngle</td></tr>
</table>
_ejMaps_

<table>
<tr>
<th>
Member Type</th><th colspan = "2">
Old API Names</th><th colspan = "2">
New API Names</th><th colspan = "2">
Comments</th></tr>
<tr>
<td>
Property</td><td colspan = "2">
zoomOnSelection</td><td colspan = "2">
enableZoomOnSelection</td><td colspan = "2">
This API is moved under new API zoomSettings.</td></tr>
<tr>
<td colspan = "2" rowspan = "6">
</td><td colspan = "2">
mapBackground</td><td colspan = "2">
background</td><td>
</td></tr>
<tr>
<td colspan = "2">
Data</td><td colspan = "2">
shapeData</td><td>
</td></tr>
<tr>
<td colspan = "2">
annotationTemplate</td><td colspan = "2">
markerTemplate</td><td>
</td></tr>
<tr>
<td colspan = "2">
annotations</td><td colspan = "2">
markers</td><td>
</td></tr>
<tr>
<td colspan = "2">
annotationDataSource</td><td colspan = "2">
N/A</td><td>
This API is removed since it is achieved in markers API.</td></tr>
<tr>
<td colspan = "2">
shapeFileLayer</td><td colspan = "2">
shapeLayer</td><td>
</td></tr>
<tr>
<td colspan = "2">
Event</td><td colspan = "2">
annotationSelected</td><td colspan = "2">
markerSelected</td><td>
</td></tr>
<tr>
<td colspan = "2" rowspan = "37">
Property</td><td colspan = "2">
bubbleSetting</td><td colspan = "2">
bubbleSettings</td><td>
</td></tr>
<tr>
<td colspan = "2">
labelSetting</td><td colspan = "2">
labelSettings</td><td>
</td></tr>
<tr>
<td colspan = "2">
legendSetting</td><td colspan = "2">
legendSettings</td><td>
</td></tr>
<tr>
<td colspan = "2">
mapType</td><td colspan = "2">
layerType</td><td>
</td></tr>
<tr>
<td colspan = "2">
shapeSetting</td><td colspan = "2">
shapeSettings</td><td>
</td></tr>
<tr>
<td colspan = "2">
annotationLabel</td><td colspan = "2">
label</td><td>
</td></tr>
<tr>
<td colspan = "2">
shapeSelectionStrokeWidth</td><td colspan = "2">
selectionStrokeWidth</td><td>
This API comes under shapeSettings.</td></tr>
<tr>
<td colspan = "2">
shapeSelectionStroke</td><td colspan = "2">
selectionStroke</td><td>
This API comes under shapeSettings.</td></tr>
<tr>
<td colspan = "2">
shapeSelectionColor</td><td colspan = "2">
selectionColor</td><td>
This API comes under shapeSettings.</td></tr>
<tr>
<td colspan = "2">
shapeFill</td><td colspan = "2">
fill</td><td>
This API comes under shapeSettings.</td></tr>
<tr>
<td colspan = "2">
shapeStroke</td><td colspan = "2">
stroke</td><td>
This API comes under shapeSettings.</td></tr>
<tr>
<td colspan = "2">
shapeColorValuepath</td><td colspan = "2">
colorValuePath</td><td>
This API comes under shapeSettings.</td></tr>
<tr>
<td colspan = "2">
shapeValuepath</td><td colspan = "2">
valuePath</td><td>
This API comes under shapeSettings.</td></tr>
<tr>
<td colspan = "2">
shapeStrokeThickness</td><td colspan = "2">
strokeThickness</td><td>
This API comes under shapeSettings.</td></tr>
<tr>
<td colspan = "2">
shapeColorPalette</td><td colspan = "2">
colorPalette</td><td>
This API comes under shapeSettings.</td></tr>
<tr>
<td colspan = "2">
bubbleColor</td><td colspan = "2">
color</td><td>
This API comes under bubbleSettings.</td></tr>
<tr>
<td colspan = "2">
bubbleColorValuepath</td><td colspan = "2">
colorValuePath</td><td>
This API comes under bubbleSettings.</td></tr>
<tr>
<td colspan = "2">
bubbleValuepath</td><td colspan = "2">
valuePath</td><td>
This API comes under bubbleSettings.</td></tr>
<tr>
<td colspan = "2">
legendPositionX</td><td colspan = "2">
positionX</td><td>
This API comes under legendSettings</td></tr>
<tr>
<td colspan = "2">
legendWidth</td><td colspan = "2">
width</td><td>
This API comes under legendSettings.</td></tr>
<tr>
<td colspan = "2">
legendHeight</td><td colspan = "2">
height</td><td>
This API comes under legendSettings.</td></tr>
<tr>
<td colspan = "2">
legendPositionY</td><td colspan = "2">
position</td><td>
This API comes under legendSettings.</td></tr>
<tr>
<td colspan = "2">
legendType</td><td colspan = "2">
type</td><td>
This API comes under legendSettings.</td></tr>
<tr>
<td colspan = "2">
legendTitle</td><td colspan = "2">
title</td><td>
This API comes under legendSettings.</td></tr>
<tr>
<td colspan = "2">
legendLeftLabel</td><td colspan = "2">
leftLabel</td><td>
This API comes under legendSettings.</td></tr>
<tr>
<td colspan = "2">
legendRightLabel</td><td colspan = "2">
rightLabel</td><td>
This API comes under legendSettings.</td></tr>
<tr>
<td colspan = "2">
legendMode</td><td colspan = "2">
mode</td><td>
This API comes under legendSettings.</td></tr>
<tr>
<td colspan = "2">
legendPosition</td><td colspan = "2">
position</td><td>
This API comes under legendSettings.</td></tr>
<tr>
<td colspan = "2">
minZoom</td><td colspan = "2">
minValue</td><td>
This API is moved under new API zoomSettings.</td></tr>
<tr>
<td colspan = "2">
maxZoom</td><td colspan = "2">
maxValue</td><td>
This API is moved under new API zoomSettings.</td></tr>
<tr>
<td colspan = "2">
zoomLevel</td><td colspan = "2">
level</td><td>
This API is moved under new API zoomSettings.</td></tr>
<tr>
<td colspan = "2">
zoomFactor</td><td colspan = "2">
factor</td><td>
This API is moved under new API zoomSettings.</td></tr>
<tr>
<td colspan = "2">
showToolTip</td><td colspan = "2">
showTooltip</td><td>
</td></tr>
<tr>
<td colspan = "2">
mouseHoverColor</td><td colspan = "2">
highlightColor</td><td>
This API comes  under API shapeSettings</td></tr>
<tr>
<td colspan = "2">
mouseHoverStroke</td><td colspan = "2">
highlightStroke</td><td>
This API comes under API shapeSettings.</td></tr>
<tr>
<td colspan = "2">
mouseHoverWidth</td><td colspan = "2">
highlightBorderWidth</td><td>
This API comes under API shapeSettings.</td></tr>
<tr>
<td colspan = "2">
subshapeFileLayers</td><td colspan = "2">
subLayers</td><td>
</td></tr>
<tr>
<td colspan = "2" rowspan = "2">
Event</td><td colspan = "2">
shapeHovered</td><td colspan = "2">
mouseover</td><td>
</td></tr>
<tr>
<td colspan = "2">
shapeUnHovered</td><td colspan = "2">
mouseleave</td><td>
</td></tr>
<tr>
<td colspan = "2" rowspan = "5">
Property</td><td colspan = "2">
minSize</td><td colspan = "2">
minValue</td><td>
This API comes under API bubbleSettings.</td></tr>
<tr>
<td colspan = "2">
maxSize</td><td colspan = "2">
maxValue</td><td>
This API comes under API bubbleSettings.</td></tr>
<tr>
<td colspan = "2">
canResize</td><td colspan = "2">
enableResize</td><td>
</td></tr>
<tr>
<td colspan = "2">
shapeIdPath</td><td colspan = "2">
shapeDataPath</td><td>
</td></tr>
<tr>
<td colspan = "2">
shapeIdTableField</td><td colspan = "2">
shapePropertyPath</td><td>
</td></tr>
<tr>
<td colspan = "2">
Enum</td><td colspan = "2">
LayerType = {        Geometry: "geometry",        OSM: "osm"    };</td><td colspan = "2">
LayerType = {Geometry: "geometry",        OSM: "osm",        Bing: "bing"    };</td><td>
</td></tr>
<tr>
<td colspan = "2">
Event</td><td colspan = "2">
panning</td><td colspan = "2">
N/A</td><td>
This API is removed.</td></tr>
</table>
_ejmMaskEdit_

<table>
<tr>
<th>
Type</th><th>
Old APIs</th><th>
New APIs</th></tr>
<tr>
<td rowspan = "2">
Methods</td><td>
persist</td><td>
enablePersistence</td></tr>
<tr>
<td>
windows.showReset</td><td>
windows.allowReset</td></tr>
</table>
_ejmMenu_

<table>
<tr>
<th>
Type</th><th>
Old APIs</th><th>
New APIs</th></tr>
<tr>
<td rowspan = "5">
Members</td><td>
android.menuType</td><td>
android.type</td></tr>
<tr>
<td>
iOS7.menuType</td><td>
iOS7.type</td></tr>
<tr>
<td>
openMenu</td><td>
showOn </td></tr>
<tr>
<td>
scrollbars</td><td>
showScrollbars</td></tr>
<tr>
<td>
windows.menuType </td><td>
windows.type</td></tr>
<tr>
<td rowspan = "12">
Methods</td><td>
showMenu </td><td>
show</td></tr>
<tr>
<td>
hideMenu </td><td>
hide</td></tr>
<tr>
<td>
enableMenu</td><td>
enable </td></tr>
<tr>
<td>
disableMenu</td><td>
disable </td></tr>
<tr>
<td>
enableMenuItem </td><td>
enableItem</td></tr>
<tr>
<td>
disableMenuItem</td><td>
disableItem</td></tr>
<tr>
<td>
enableOverFlowMenuItem</td><td>
enableOverFlowItem</td></tr>
<tr>
<td>
disableOverFlowMenuItem</td><td>
disableOverFlowItem</td></tr>
<tr>
<td>
enableOverFlowMenu</td><td>
enableOverFlow </td></tr>
<tr>
<td>
disableOverFlowMenu</td><td>
disableOverFlow</td></tr>
<tr>
<td>
addMenuItem </td><td>
addItem</td></tr>
<tr>
<td>
removeMenuItem</td><td>
removeItem </td></tr>
<tr>
<td>
Enum</td><td>
iOS7.menuType</td><td>
iOS7.Type</td></tr>
<tr>
<td>
</td><td>
iOS7.cancelButtonColor</td><td>
iOS7.CancelButtonColor</td></tr>
<tr>
<td>
</td><td>
android.menuType</td><td>
Android.Type</td></tr>
<tr>
<td>
</td><td>
windows.menuType</td><td>
Windows.Type</td></tr>
</table>
_ejmNumeric_

<table>
<tr>
<th>
Type</th><th>
Old APIs</th><th>
New APIs</th></tr>
<tr>
<td rowspan = "4">
Members</td><td>
Decimals</td><td>
decimalPlaces</td></tr>
<tr>
<td>
Persist</td><td>
enablePersistence</td></tr>
<tr>
<td>
strictMode</td><td>
enableStrictMode</td></tr>
<tr>
<td>
waterMarkText</td><td>
watermarkText</td></tr>
</table>
_ejmPassword_

<table>
<tr>
<th>
Type</th><th>
Old APIs</th><th>
New APIs</th></tr>
<tr>
<td rowspan = "2">
Methods</td><td>
persist</td><td>
enablePersistence</td></tr>
<tr>
<td>
windows.showReset</td><td>
windows.allowReset</td></tr>
</table>
_ejmProgressBar_

<table>
<tr>
<th>
Type</th><th>
Old APIs</th><th>
New APIs</th></tr>
<tr>
<td rowspan = "5">
Members</td><td>
allowCustomText</td><td>
enableCustomText </td></tr>
<tr>
<td>
persist</td><td>
enablePersistence </td></tr>
<tr>
<td>
stepValue</td><td>
incrementStep </td></tr>
<tr>
<td>
min</td><td>
minValue </td></tr>
<tr>
<td>
max </td><td>
maxValue</td></tr>
</table>
_ejRangeNavigator_

<table>
<tr>
<th>
Member Type</th><th colspan = "2">
Old APIs</th><th>
New APIs</th><th>
Comments</th></tr>
<tr>
<td rowspan = "20">
Property</td><td colspan = "2">
canResize</td><td>
enableAutoResizing</td><td>
</td></tr>
<tr>
<td colspan = "2">
isRTL</td><td>
enableRTL</td><td>
</td></tr>
<tr>
<td colspan = "2">
navigatorStyle</td><td>
navigatorStyleSettings</td><td>
</td></tr>
<tr>
<td colspan = "2">
navigatorStyle.border.strokedasharray</td><td>
navigatorStyleSettings.border.dashArray</td><td>
</td></tr>
<tr>
<td colspan = "2">
labelSettings.higherLevel.gridLineStyle.strokedasharray</td><td>
labelSettings.higherLevel.gridLineStyle.dashArray</td><td>
</td></tr>
<tr>
<td colspan = "2">
labelSettings.lowerLevel.gridLineStyle.strokedasharray</td><td>
labelSettings.lowerLevel.gridLineStyle.dashArray</td><td>
</td></tr>
<tr>
<td colspan = "2">
snappingMode</td><td>
allowSnapping</td><td>
</td></tr>
<tr>
<td colspan = "2">
deferredUpdate</td><td>
enableDeferredUpdate</td><td>
</td></tr>
<tr>
<td colspan = "2">
tooltipSettings.labelstyles.font</td><td>
tooltipSettings.font</td><td>
labelstyles in tooltipSettings are removed and font property is moved directly undertoolSettings.</td></tr>
<tr>
<td colspan = "2">
labelSettings.labelstyles</td><td>
labelSettings.style</td><td>
</td></tr>
<tr>
<td colspan = "2">
labelSettings.higherLevel.labelstyles</td><td>
labelSettings.higherLevel.style</td><td>
</td></tr>
<tr>
<td colspan = "2">
labelSettings.lowerLevel .labelstyles</td><td>
labelSettings.lowerLevel.style</td><td>
</td></tr>
<tr>
<td colspan = "2">
font.fontFamily                    font.fontStyle                   font.fontWeight</td><td>
font.familyfont.stylefont.weight</td><td>
</td></tr>
<tr>
<td colspan = "2">
Range</td><td>
rangeSettings</td><td>
</td></tr>
<tr>
<td colspan = "2">
selectedRange</td><td>
selectedRangeSettings</td><td>
</td></tr>
<tr>
<td colspan = "2">
Size</td><td>
sizeSettings</td><td>
</td></tr>
<tr>
<td colspan = "2">
tooltip</td><td>
tooltipSettings</td><td>
</td></tr>
<tr>
<td colspan = "2">
zoomCordinates</td><td>
zoomFactorzoomPositon</td><td>
</td></tr>
<tr>
<td colspan = "2">
localization</td><td>
locale</td><td>
</td></tr>
<tr>
<td colspan = "2">
dataSource.data:”chartdata”,dataSource.xName:”xValue”,dataSource.yName:”yValue”</td><td>
dataSource:”chartdata”,xName:”xValue”,yName:”yValue”</td><td>
Removed dataSource and movedthe properties under dataSource directly to the rangenavigatormodel, whereas the data property is renamed as dataSource.</td></tr>
<tr>
<td>
Member Type</td><td colspan = "2">
Old Method Names</td><td>
New Method Names</td><td>
Comments</td></tr>
<tr>
<td>
Method</td><td colspan = "2">
rendernavigator</td><td>
renderNavigator</td><td>
</td></tr>
<tr>
<td>
Member Type</td><td>
Event Name</td><td>
Old Argument Names</td><td>
New Argument Names</td><td>
Comments</td></tr>
<tr>
<td rowspan = "2">
Event</td><td>
loaded</td><td>
args:{cancelCancelData={Model}modeltype}</td><td>
args:{cancelCanceldata={model}modeltype}</td><td>
Modified args.Data.Removed args.Cancel.</td></tr>
<tr>
<td>
load</td><td>
args:{cancelCancelData={Model}modeltype}</td><td>
args:{cancelCanceldata={model}modeltype}</td><td>
Modified args.Data.Removed args.Cancel.</td></tr>
</table>
_ejmRating_

<table>
<tr>
<th>
Type</th><th>
Old APIs</th><th>
New APIs</th></tr>
<tr>
<td rowspan = "2">
Members</td><td>
persist</td><td>
enablePersistence</td></tr>
<tr>
<td>
currentValue</td><td>
value </td></tr>
<tr>
<td rowspan = "3">
Methods</td><td>
getCurrentValue</td><td>
getValue </td></tr>
<tr>
<td>
showRating</td><td>
show </td></tr>
<tr>
<td>
hideRating</td><td>
hide </td></tr>
<tr>
<td rowspan = "3">
Events</td><td>
click</td><td>
tap </td></tr>
<tr>
<td>
valueChanged </td><td>
change</td></tr>
<tr>
<td>
Move</td><td>
touchMove </td></tr>
</table>
_ejmRotator_

<table>
<tr>
<th>
Type</th><th>
Old APIs</th><th>
New APIs</th></tr>
<tr>
<td rowspan = "3">
Members</td><td>
currentIndex</td><td>
currentItemIndex</td></tr>
<tr>
<td>
header</td><td>
showHeader</td></tr>
<tr>
<td>
pager</td><td>
showPager</td></tr>
</table>
_ejmScrollPanel_

<table>
<tr>
<th>
Type</th><th>
Old APIs</th><th>
New APIs</th></tr>
<tr>
<td rowspan = "17">
Members</td><td>
resizeScrollbar</td><td>
enableResize</td></tr>
<tr>
<td>
fadeScrollbar</td><td>
enableFade</td></tr>
<tr>
<td>
shrinkScrollbar</td><td>
enableShrink</td></tr>
<tr>
<td>
setAutoHeight</td><td>
autoAdjustHeight</td></tr>
<tr>
<td>
relative</td><td>
isRelative</td></tr>
<tr>
<td>
wheelSpeed</td><td>
wheelSpeed</td></tr>
<tr>
<td>
interactiveScrollbars</td><td>
enableInteraction</td></tr>
<tr>
<td>
hrScroll</td><td>
enableHrScroll</td></tr>
<tr>
<td>
verScroll</td><td>
enableVrScroll</td></tr>
<tr>
<td>
useDisplacement</td><td>
enableDisplacement</td></tr>
<tr>
<td>
Bounce</td><td>
enableBounce</td></tr>
<tr>
<td>
useTransition</td><td>
enableTransition</td></tr>
<tr>
<td>
useTransform</td><td>
enableTransform</td></tr>
<tr>
<td>
Scrollbars</td><td>
showScrollbars</td></tr>
<tr>
<td>
mouseWheel</td><td>
enableMouseWheel</td></tr>
<tr>
<td>
Zoom</td><td>
enableZoom</td></tr>
<tr>
<td>
nativeScroll</td><td>
enableNativeScrolling</td></tr>
<tr>
<td>
Events</td><td>
scrollMove</td><td>
scroll</td></tr>
</table>
_ejmSlider_

<table>
<tr>
<th>
Type</th><th>
Old APIs</th><th>
New APIs</th></tr>
<tr>
<td rowspan = "6">
Members</td><td>
animate</td><td>
enableAnimation</td></tr>
<tr>
<td>
persist</td><td>
enablePersistence</td></tr>
<tr>
<td>
range</td><td>
enableRange</td></tr>
<tr>
<td>
step</td><td>
incrementStep</td></tr>
<tr>
<td>
startValue</td><td>
minValue</td></tr>
<tr>
<td>
endValue</td><td>
maxValue</td></tr>
<tr>
<td>
Events</td><td>
start</td><td>
touchStart</td></tr>
</table>
_ejmSplitPane_

<table>
<tr>
<th>
Type</th><th>
Old APIs</th><th>
New APIs</th></tr>
<tr>
<td rowspan = "3">
Members</td><td>
leftScrolling</td><td>
allowLeftPaneScrolling</td></tr>
<tr>
<td>
rightScrolling</td><td>
allowRightPaneScrolling</td></tr>
<tr>
<td>
android->showToolbarBackNavigator</td><td>
android->showBackNavigator</td></tr>
</table>
___ejmTab_

<table>
<tr>
<td>
Type</td><td>
Old APIs</td><td>
New APIs</td></tr>
<tr>
<td rowspan = "10">
Members</td><td>
loadAjaxContent</td><td>
enableAjax</td></tr>
<tr>
<td>
ajaxOptions</td><td>
ajaxSettings</td></tr>
<tr>
<td>
showBadge</td><td>
badge.enabled</td></tr>
<tr>
<td>
badgeValue</td><td>
badge.value</td></tr>
<tr>
<td>
maxBadgeValue</td><td>
badge.maxValue</td></tr>
<tr>
<td>
iOS7.showMoreBadge</td><td>
iOS7.overflowBadge.enabled</td></tr>
<tr>
<td>
iOS7.moreBadgeMaxValue</td><td>
iOS7.overflowBadge.maxValue</td></tr>
<tr>
<td>
iOS7.moreBadgeValue</td><td>
iOS7.overflowBadge.value</td></tr>
<tr>
<td>
android. showImage</td><td>
android.showImage</td></tr>
<tr>
<td>
windows.customText</td><td>
windows.enableCustomText</td></tr>
<tr>
<td rowspan = "3">
Events</td><td>
ajaxLoadSuccess</td><td>
ajaxSuccess</td></tr>
<tr>
<td>
ajaxLoadError</td><td>
ajaxError</td></tr>
<tr>
<td>
ajaxLoadComplete</td><td>
ajaxComplete</td></tr>
<tr>
<td rowspan = "11">
Methods</td><td>
addTabItem</td><td>
addItem</td></tr>
<tr>
<td>
addMoreTabItem</td><td>
addOverflowItem</td></tr>
<tr>
<td>
disableTabContent</td><td>
disableContent</td></tr>
<tr>
<td>
disableTab</td><td>
disableItem</td></tr>
<tr>
<td>
enableTabContent</td><td>
enableContent</td></tr>
<tr>
<td>
enableTab</td><td>
enableItem</td></tr>
<tr>
<td>
getTabItemCount</td><td>
getItemsCount</td></tr>
<tr>
<td>
getMoreTabItemCount</td><td>
getOverflowItemCount</td></tr>
<tr>
<td>
removeTabItem</td><td>
removeItem</td></tr>
<tr>
<td>
removeMoreTabItem</td><td>
removeOverflowItem</td></tr>
<tr>
<td>
selectTabItem</td><td>
selectItem</td></tr>
</table>
_ejmTextArea_

<table>
<tr>
<th>
Type</th><th>
Old APIs</th><th>
New APIs</th></tr>
<tr>
<td rowspan = "2">
Methods</td><td>
persist</td><td>
enablePersistence</td></tr>
<tr>
<td>
windows.showReset</td><td>
windows.allowReset</td></tr>
</table>
_ejmTextbox_

<table>
<tr>
<th>
Type</th><th>
Old APIs</th><th>
New APIs</th></tr>
<tr>
<td rowspan = "2">
Methods</td><td>
persist</td><td>
enablePersistence</td></tr>
<tr>
<td>
windows.showReset</td><td>
windows.allowReset</td></tr>
</table>
_ejmTile_

<table>
<tr>
<th>
Type</th><th>
Old APIs</th><th>
New APIs</th></tr>
<tr>
<td rowspan = "5">
Members</td><td>
showLiveTile</td><td>
enableLiveTile</td></tr>
<tr>
<td>
showTileIcon</td><td>
showIcon</td></tr>
<tr>
<td>
showTileBadge</td><td>
badge.enabled</td></tr>
<tr>
<td>
badgeValue</td><td>
badge.value</td></tr>
<tr>
<td>
maxBadgeValue</td><td>
badge.maxValue</td></tr>
<tr>
<td rowspan = "3">
Methods</td><td>
setShowTileIcon</td><td>
showIcon</td></tr>
<tr>
<td>
setTileText</td><td>
setText</td></tr>
<tr>
<td>
setTextAlign</td><td>
setTextAlignment</td></tr>
</table>
_ejmTimePicker_

<table>
<tr>
<th>
Type</th><th>
Old APIs</th><th>
New APIs</th></tr>
<tr>
<td rowspan = "2">
Members</td><td>
hourMode           </td><td>
hourFormat</td></tr>
<tr>
<td>
defaultTime           </td><td>
value</td></tr>
</table>
_ejTreeMap_

<table>
<tr>
<th>
Member Type</th><th>
Old API Names</th><th>
New API Names</th><tdh>
Comments</th></tr>
<tr>
<td rowspan = "9">
Property</td><td>
treeMapLegend</td><td>
legendSettings</td><td>
</td></tr>
<tr>
<td>
leafItemSetting</td><td>
leafItemSettings</td><td>
</td></tr>
<tr>
<td>
legendIconHeight</td><td>
iconHeight</td><td>
This API comes under legendSettings.</td></tr>
<tr>
<td>
legendIconWidth</td><td>
iconWidth</td><td>
This API comes under legendSettings.</td></tr>
<tr>
<td>
legendTemplate</td><td>
template</td><td>
This API comes under legendSettings.</td></tr>
<tr>
<td>
canResize</td><td>
enableResize</td><td>
</td></tr>
<tr>
<td>
showItems</td><td>
N/A</td><td>
This API is removed from leafItemSettings since it is achieved in showLabels API.</td></tr>
<tr>
<td>
showItems</td><td>
N/A</td><td>
This API is removed from treeMapLevel since it is achieved in showLabels API.</td></tr>
<tr>
<td>
labelTemplate</td><td>
itemTemplate</td><td>
This API comes under leafItemSettings. You can use this template to customize the item with label.</td></tr>
</table>
_ejmToggleButton_

<table>
<tr>
<th>
Type</th><th>
Old APIs</th><th>
New APIs</th></tr>
<tr>
<td>
Members</td><td>
persist</td><td>
enablePersistence</td></tr>
<tr>
<td>
Events</td><td>
stateChange</td><td>
change</td></tr>
</table>
_ejmToolBar_

<table>
<tr>
<th>
Type</th><th>
Old APIs</th><th>
New APIs</th></tr>
<tr>
<td rowspan = "3">
Members</td><td>
toolbarPosition </td><td>
position</td></tr>
<tr>
<td>
android.showTitleIconNavigator</td><td>
android.showTitleIcon</td></tr>
<tr>
<td>
android.splitView </td><td>
android.enableSplitView </td></tr>
<tr>
<td rowspan = "7">
Methods</td><td>
addNewItem</td><td>
addItem</td></tr>
<tr>
<td>
removeIconByIndex</td><td>
removeItemg</td></tr>
<tr>
<td>
setShowIcon</td><td>
showItem</td></tr>
<tr>
<td>
setHideIcon</td><td>
hideItem</td></tr>
<tr>
<td>
setEnableIcon</td><td>
enableItem</td></tr>
<tr>
<td>
setDisableIcon</td><td>
disableItem</td></tr>
<tr>
<td>
removeIconByIndex</td><td>
removeItem</td></tr>
</table>


