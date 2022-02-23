# hlp22docs

Team documents for HLP22 project work individual code assessment

Fork and clone this repo. Edit your single given Team document only (e.g. Team1.md).

Any member of Team can submit PRs to my repo for their team at any time, every commit should be agreed by team. Only one commit is required.

**1st commit with initial (and probably final) allocations of code to Team members must be before Wednesday 23rd 16:00.**

* Write down every top-level function, in its initial order in files,  and who is responsible for it, on a single line (line numbers are unstable).
* Give team members as IC logins
* Add changes in section below

## Example content of TeamN.md file

# Team members

* delete this and replace by your team members*

| Name | IC user | github login
|------|----------|-------------
| Timothy Moores | tjm1518 | 1rre
| Hyunjoon Jeon | hj1119 | HyunjoonJeon
| Zion Darko | zd819 | zd819
| Chackrarat Kitikul | ck1419 | ck1419
| Aleksandar Limonov | al1919 | al1919

# Individual Contributions

## Symbol

## Symbol
### Types
[x] `Rotation` - tjm1518  
[ ] `Symbol` - tjm1518 & hj1119  
[ ] `RenderSymbolProps` - tjm1518  
### Member 1
[x] `posDiff/2` - tjm1518  
[x] `posAdd/2` - tjm1518  
[x] `posOf/2` - tjm1518  
[ ] `title/2` - tjm1518  
[ ] `bustitle/2` - tjm1518  
[ ] `prefix/1` - tjm1518  
[ ] `gateDecoderType/1` - tjm1518  
[ ] `portDecName/1` - tjm1518  
[ ] `portLists/3` - tjm1518  
[ ] `roundToN/2` - tjm1518  
[ ] `customToLength/1` - tjm1518  
[ ] `makeComp/4` - tjm1518  
[ ] `makeComponent/2` - tjm1518  
[ ] `addToPortModel/2` - tjm1518  
[ ] `getPortPosEdgeGap/1` - tjm1518  
[ ] `getPortPos/2` - tjm1518  
[ ] `getPortPosModel/2` - tjm1518  
[ ] `addText/6` - tjm1518  
[ ] `portCircles/2` - tjm1518  
[ ] `portText/4` - tjm1518  
[ ] `drawPortsText/3` - tjm1518  
[ ] `drawPorts/3` - tjm1518  
[ ] `createPolygon/3` - tjm1518  
[ ] `createBiColorPolygon/5` - tjm1518  
[ ] `addInvertor/4` - tjm1518  
[ ] `addHorizontalLine/4` - tjm1518  
[ ] `outlineColor/1` - tjm1518  
[ ] `addHorizontalColorLine/5` - tjm1518  
[ ] `compSymbol/6` - tjm1518  
[ ] `init/0` - tjm1518  
[ ] `renderSymbol/0` - tjm1518  
[ ] `mapIntoLists/1` - tjm1518  
[ ] `view/2` - tjm1518  
### Member 2
[ ] `getBoundingBoxofSymbol/1` - hj1119
[ ] `getBoundingBoxes/1` - hj1119
[ ] `getOneBoundingBox/2` - hj1119
[ ] `getSymbolPos/2` - hj1119
[ ] `getInputPortPositionMap/2` - hj1119
[ ] `getOutputPortPositionMap/2` - hj1119
[ ] `getPort/2` - hj1119
[ ] `getPortLocations/2` - hj1119
[ ] `getInputPortLocation/2` - hj1119
[ ] `getOutputPortLocation/2` - hj1119
[ ] `getOnePortLocation/3` - hj1119
[ ] `getOnePortLocationNew/3` - hj1119
[ ] `getTwoPortLocations/3` - hj1119
[ ] `getCopiedSymbols/1` - hj1119
[ ] `filterString/1` - hj1119
[ ] `regex/1` - hj1119
[ ] `getCompList/2` - hj1119
[ ] `getIndex/2` - hj1119
[ ] `labelGenNumber/3` - hj1119
[ ] `generateLabel/2` - hj1119
[ ] `pasteSymbols/2` - hj1119
[ ] `getEquivalentCopiedPorts/4` - hj1119
[ ] `addSymbol/4` - hj1119
[ ] `changeNumberOfBitsf/3` - hj1119
[ ] `changeLsbf/3` - hj1119
[ ] `changeConstantf/4` - hj1119
[ ] `update/2` - hj1119
[ ] `extractComponent/2` - hj1119
[ ] `extractComponents/2` - hj1119

### Symbol Function Ownership Changes

20 Feb dfun --> empty

22 Feb bfun --> empty

*List anything special here about who did what if needed*

## Buswire

### Types
[x] `Segment` - ck1419 & & al1919 & zd819  
[x] `Wire` - al1919 & & ck1419 & zd819  

----- Member 1 -----

[ ] getSegmentOrientation - ck1419

[ ] getSegmentPos - ck1419

[ ] xyToLength - ck1419

[ ] segmentsToVertices - ck1419

[ ] makeInitialWireVerticesList - ck1419

[ ] xyToLength - ck1419

[ ] segmentsToVertices - ck1419

[ ] makeInitialWireVerticesList - ck1419

[ ] inferDirectionfromVertices - ck1419

[ ] xyVerticesToSegments - ck1419

[ ] issieVerticesToSegments - ck1419

[ ] extractConnection - ck1419

[ ] extractConnections - ck1419

[ ] onSegment - ck1419

[ ] findRotation - ck1419

[ ] segmentIntersectsSegment - ck1419

[ ] distanceBetweenTwoPoints - ck1419

[ ] makeInitialSegmentsList - ck1419

[ ] segmentsToVertices - ck1419

[ ] renderSegment - ck1419

[ ] segmentIntersectsSegmentCoordinates - ck1419

[ ] getTopLeftAndBottomRightCorner - ck1419

[ ] segmentIntersectsBoundingBoxCoordinates - ck1419

[ ] extractConnection - ck1419

[ ] distanceFromPointToSegment - ck1419

[ ] routeGivenWiresBasedOnPortPositions - ck1419

[ ] getIntersectingSegments - ck1419


----- Member 2 -----


[ ] getClickedSegment - al1919

[ ] checkSegmentAngle - al1919

[ ] segPointsLeft - al1919

[ ] segXDelta - al1919

[ ] moveXJoinPos - al1919

[ ] changeLengths - al1919

[ ] getSafeDistanceForMove - al1919

[ ] removeRedundantSegments - al1919

[ ] moveSegment - al1919

[ ] memoOf - al1919

[ ] singleWireView - al1919

[ ] MapToSortedList - al1919

[ ] view - al1919

[ ] makeAllJumps - al1919

[ ] updateWireSegmentJumps - al1919

[ ] resetWireSegmentJumps - al1919

[ ] init - al1919

[ ] getConnectedWires - al1919

[ ] filterWiresByCompMoved - al1919

[ ] autorouteWire - al1919

[ ] revSegments - al1919

[ ] addPosPos - al1919

[ ] getManhattanDistance - al1919

[ ] moveAll - al1919

[ ] transformSeg - al1919

[ ] topology - al1919

[ ] partialAutoRoute - al1919


----- Member 3 -----

[ ] ppSeg - zd819

[ ] pp - zd819

[ ] partialAutoRoute - zd819

[ ] negXYPos - zd819

[ ] moveWire - zd819

[ ] updateWire - zd819

[ ] updateWires - zd819

[ ] update - zd819

[ ] wireIntersectsBoundingBox - zd819

[ ] getIntersectingWires - zd819

[ ] getWireIfClicked - zd819

[ ] pasteWires - zd819

### Buswire changes

20 Feb dfun --> empty

22 Feb bfun --> empty

## Other Module Changes

* any changes made to other modules *

Sheet.getWireBBox  - ck1419

Sheet.boolList   - ck1419



