# Team 8: hlp22docs

Team documents for HLP22 project work individual code assessment

Fork and clone this repo. Edit your single given Team document only (e.g. Team1.md).

Any member of Team can submit PRs to my repo for their team at any time, every commit should be agreed by team. Only one commit is required.

**1st commit with initial (and probably final) allocations of code to Team members must be before Wednesday 23rd 16:00.**

* Write down every top-level function, in its initial order in files,  and who is responsible for it, on a single line (line numbers are unstable).
* Give team members as IC logins
* Add changes in section below

# Team members

* delete this and replace by your team members*

| Name | IC user | github login
|------|----------|-------------
| Xin Wang | xw2519 | xw2519
| Leonardo Garofalo | lg519 | lg519
| Dominic Clough | dac219 | dac219
| Bertil de Germay de Cirfontaine | bd519 | bd519
| Tanguy Perron | tlp19 | tlp19

# Individual Contributions

## Symbol

*keep this list up to date*

- Line 78 - 78: `convertDegtoRad` - xw2519
- Line 80 - 82: `convertRelativeToSymbolCenter` - xw2519
- Line 84 - 86: `convertRelativeToTopLeft` - xw2519
- Line 88 - 94: `convertSymbolPointsToString` - xw2519
- Line 96 - 97: `flipSymbol` - xw2519
- Line 99 - 99: `getSymbolPoints` - xw2519
- Line 101 - 101: `posAdd` - xw2519
- Line 103 - 103: `posDiff` - xw2519
- Line 105 - 105: `posOf` - xw2519
- Line 107 - 109: `rotatePoint` - xw2519
- Line 111 - 125: `rotateSymbol` - xw2519
- Line 129 - 129: `init` - xw2519
- Line 131 - 203: `initComponent` - xw2519
- Line 205 - 209: `initSymbolCharacteristics` - xw2519
- Line 211 - 274: `initSymbolPoints` - xw2519
- Line 276 - 292: `makeSymbol` - xw2519
- Line 296 - 303: `addToPortModel` - xw2519
- Line 305 - 325: `getPortPos` - xw2519
- Line 327 - 328: `getModelPortPos` - xw2519
- Line 332 - 335: `addText` - xw2519
- Line 339 - 381: `addPortText` - xw2519
- Line 383 - 405: `addPortTitle` - xw2519
- Line 407 - 417: `addSymbolLabel` - xw2519
- Line 419 - 495: `addSymbolText` - xw2519
- Line 499 - 504: `addOutlineColor` - xw2519
- Line 506 - 507: `createPolygon` - xw2519
- Line 509 - 519: `drawBiColorPolygon` - xw2519
- Line 521 - 523: `drawHorizontalLine` - xw2519
- Line 525 - 528: `drawHorizontalColorLine` - xw2519
- Line 530 - 531: `drawPortCircle` - xw2519
- Line 533 - 535: `drawVerticalLine` - xw2519
- Line 537 - 540: `drawVerticalColorLine` - xw2519
- Line 544 - 549: `drawPorts` - xw2519
- Line 551 - 566: `drawArrow` - xw2519
- Line 568 - 604: `drawSymbolCharacteristics` - xw2519
- Line 606 - 675: `drawSymbolShape` - xw2519
- Line 679 - 687: `createSymbol` - xw2519
- Line 696 - 704: `renderSymbol` - xw2519
- Line 706 - 717: `convertMapsIntoLists` - xw2519
- Line 719 - 729: `view` - xw2519
- `getBoundingBoxofSymbol` -lg519
- `getBoundingBoxes` -lg519
- `getOneBoundingBox` -lg519
- `getSymbolPos` -lg519
- `getInputPortsPositionMap` -lg519
- `getOutputPortsPositionMap` -lg519
- `getPortLocations` -lg519
- `getInputPortLocation` -lg519
- `getOutputPortLocation` -lg519
- `getOnePortLocation` -lg519
- `getOnePortLocationNew` -lg519
- `getTwoPortLocations` -lg519
- `getCopiedSymbols` -lg519
- `getCompList` -lg519
- `filterString` -lg519
- `regex` -lg519
- `getIndex` -lg519
- `labelGenNumber` -lg519
- `generateLabel` -lg519
- `pasteSymbols` -lg519
- `getEquivalentCopiedPorts` -lg519
- `changeNumberOfBitsf` -lg519
- `changeLsbf` -lg519
- `changeConstantf` -lg519
- `update` -lg519
- `extractComponent` -lg519
- `extractComponents` -lg519

### Symbol Function Ownership Changes

## Buswire

*as for symbol above, list initial names of functions in initial line order and who is responsible*

- `segmentsToVertices` - dac219
- `makeInitialWireVerticesList` - tlp19
- `inferDirectionfromVertices` - dac219
- `xyVerticesToSegments` - tlp19
- `issieVerticesToSegments` - dac219
- `extractConnection` - dac219
- `extractConnections` - dac219
- `onSegment` - dac219
- `orientation` - dac219
- `getAbsXY` - dac219
- `segmentIntersectsSegment` - dac219
- `makeSegPos` - dac219
- `distanceBetweenTwoPoints` - dac219
- `makeInitialSegmentsList` - tlp19
- `renderSegment` - dac219
- `memoOf` - dac219
- `singleWireView` - dac219
- `MapToSortedList` - dac219
- `view` - dac219
- `segmentIntersectsSegmentCoordinates` - tlp19
- `getTopLeftAndBottomRightCorner` - tlp19
- `segmentIntersectsBoundingBoxCoordinates` - tlp19
- `distanceFromPointToSegment` - tlp19
- `routeGivenWiresBasedOnPortPositions` - tlp19
- `getIntersectingSegments` - tlp19
- `getClosestSegment` - tlp19
- `getClickedSegment` - tlp19
- `checkSegmentAngle` - tlp19
- `segPointsLeft` - tlp19
- `segXDelta` - tlp19
- `moveXJoinPos` - tlp19
- `changeLengths` - tlp19
- `getSafeDistanceForMove` - tlp19
- `removeRedundantSegments` - tlp19
- `moveSegment` - tlp19
- `init` - tlp19
- `getConnectedWires` - tlp19
- `filterWiresByCompMoved` - tlp19
- `autorouteWire` - tlp19
- `revSegments` - tlp19
- `addPosPos` - tlp19
- `moveEnd` - tlp19
- `moveStart` - tlp19
- `moveAll` - tlp19
- `transformXY` - tlp19
- `transformSeg` - tlp19
- `topology` - tlp19
- `partialAutoRoute` - tlp19
- `negXYPos` - tlp19
- `moveWire` - tlp19
- `updateWire` - tlp19


- `makeAllJumps` - bd519
- `updateWireSegmentJumps` - bd519
- `resetWireSegmentJumps` - bd519
- `updateWires` - bd519
- `update` - bd519
- `wireIntersectsBoundingBox` - bd519
- `getIntersectingWires` - bd519
- `getWireIfClicked` - bd519
- `pasteWires` - bd519
- `getPortIdsOfWires` - bd519


### Buswire changes

- 28 Feb `makeInitialWireVerticesList` --> tlp19
- 28 Feb `xyVerticesToSegments` --> tlp19
- 28 Feb `makeInitialSegmentsList` --> tlp19


## Other Module Changes

- 27 Feb: Line 824 - 1112: `Sheet.fs: update` - xw2519 
  
    Modified `update` function to register keypresses `R` and `F` and call the associated functions.

- 27 Feb: Line 160 - 181: `Renderer.fs: editMenu` - xw2519 

    Modified `editMenu` to recognise keypresses `R` and `F`.

- 1 Mar: Line 824 - 1112: `Sheet.fs: update` - lg519

    Simplified logic to conform to ISSIE guidelines.






