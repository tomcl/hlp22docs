# Team members


| Name | IC user | github login
|------|----------|-------------
| Josiah Mendes | jam419 | JosiahMendes
| Raghav Viswakumar | rv519 | Ragviswa
| Matei Tanase | mt1819 | Matteus247
| Yuliang Zhu | yz8819 | JasonZhuYL
| Yujie Wang | yw2919 | 0x6770
| Gowoon Kim | gk518 | woonmoon

# Individual Contributions

## Symbol

- `posDiff` - mt1819
- `posAdd` - mt1819
- `posOf` - mt1819 -> removed
- `symbolTitle` - mt1819 -> merged and removed
- `busTitle` - mt1819 -> merged and removed
- `addBusTitle` - mt1819 -> merge result of the two above functions
- `prefix` - mt1819
- `gateDecoderType` - mt1819 -> setCompTitle
- `portDecName` - mt1819 -> mapPortNames
- `portList` - mt1819 -> makePortList
- `customToLength` - mt1819
- `makeComp` - mt1819
- `symbolPortArgs` - mt1819 -> New
- `createNewSymbol` - mt1819
- `addToPortModel` - mt1819
- `getPortPosEdgeGap` - mt1819
- `getPortPos` - mt1819
- `getPortPosModel` - mt1819
- `addText` - mt1819
- `portCircles` - mt1819
- `drawPortsText` - mt1819
- `drawPorts` - mt1819
- `createPolygon` - mt1819
- `createBiColorPolygon` - mt1819
- `addInvertor` - mt1819
- `addClock` - mt1819
- `addHorizontalLine` - mt1819
- `outlineColor` - mt1819
- `addHorizontalColorLine` - mt1819
- `compSymbol` - mt1819
- `init` - mt1819
- `RenderSymbolProps` - mt1819
- `renderSymbol` - mt1819
- `MapsIntoLists` - mt1819
- `view` - mt1819
- 

- `posDiff` - rv519
- `posAdd` - rv519
~~- `posOf` - rv519~~
- **New** rotatePorts - rv519
- `addText` - rv519
~~- `title` - rv519~~
- `busTitle` -> `getbusTitle` - rv519
- `prefix` -> `getSymbolLabel` - rv519
- `gateDecoderType` -> `getSymbolTitle` - rv519
- `portDecName` -> `getSymbolPortsTitle` - rv519
~~- `portList` - rv519~~
~~- `customToLength` - rv519~~
- `makeComp` -> createNewComponent - rv519
- **New** `createPortsLoc` - rv519
- `createNewSymbol` - rv519
- **New** `movePortClockwise` - rv519
- **New** `movePortCounterClockwise` - rv519
- `addToPortModel` - rv519
~~- `getPortPosEdgeGap` - rv519~~
- **New** `getPortPosLoc` - rv519
- `getPortPos` - rv519
~~- `getPortPosModel` - rv519~~
~~- `portCircles` - rv519~~
- **New** `portText` - rv519
- `drawPortsText` - rv519
- `drawPorts` - rv519
~~- `createPolygon` - rv519~~
~~- `createBiColorPolygon` - rv519~~
- `addInvertor` - rv519
- `addClock` - rv519
~~- `addHorizontalLine` rv519~~
~~- `outlineColor` - rv519~~
- `addHorizontalColorLine` -> `drawLine rv519
- `compSymbol` -> `drawSymbol` rv519
- `init` - rv519
- `RenderSymbolProps` - rv519
- `renderSymbol` - rv519
~~- `MapsIntoLists` - rv519`~~
- `view` - rv519


- `getBoundingBoxofSymbol` -jam419
- `getBoundingBoxes` -jam419
- `getOneBoundingBox` -jam419
- ~~`getSymbolPos` -jam419~~
- `getInputPortsPositionMap` -jam419
- `getOutputPortsPositionMap` -jam419
- `getPortLocations` -jam419
- `getInputPortLocation` -jam419
- `getOutputPortLocation` -jam419
- ~~`getOnePortLocation` -jam419~~
- `getOnePortLocationNew` -jam419
- `getTwoPortLocations` -jam419
- `getCopiedSymbols` -jam419
- `filterString` -> `removeTerminalNumerics` -jam419
- `regex` -> `getCompLabelNum` -jam419
- `getCompList` -> `getFilteredCompList` -jam419
- `getIndex` -jam419
- `labelGenNumber` -jam419
- `generateLabel` -jam419
- `pasteSymbols` -jam419
- `getEquivalentCopiedPorts` -jam419
- `addSymbol` -jam419
- ~~`changeNumberOfBitsf` -jam419~~
- ~~`changeLsbf` -jam419~~
- ~~`changeConstantf` -jam419~~
- `update` -jam419
- `extractComponent` -jam419
- `extractComponents` -jam419

### Symbol Function Ownership Changes

2 March jam419 -> refactoring and removed several functions including `getSymbolPos`, `getOnePortLocation`, `changeNumberOfBitsf`, `changeLsbf`, `changeConstantf` and also renamed functions as above. 

## Buswire

- `convertRISegsToVertices` -> `wireToVertices` - yw2919
- `makeInitialWireVerticesList` - yz8819
- `xyVerticesToSegments` - yz8819
- `issieVerticesToRISegments` - yz8819
- `extractConnection` - yz8819
- `extractConnections` - yz8819
- `onSegment` - yz8819
- `segmentIntersectsSegmentRI` - yz8819
- `makeInitialRISegmentsList` - yz8819
- `renderSegment` - yz8819
- `singleWireView` - yz8819
- `view` - yz8819

- ~~`segmentIntersectsSegmentCoordinates` - yw2919~~
- ~~`routeGivenWiresBasedOnPortPositions` - yw2918~~
- ~~`checkSegmentAngle` - yw2918~~
- ~~`segPointsLeft` - yw2919~~
- ~~`segXDelta` - yw2919~~
- ~~`moveXJoinPos` - yw2919~~
- ~~`changeLengths` - yw2918~~
- ~~`removeRedundantSegments` - yw2918~~
- ~~`addPosPos` - yw2919~~
- ~~`moveEnd` - yw2919~~
- ~~`moveStart` - yw2919~~
- ~~`moveAll` - yw2919~~
- ~~`transformXY` - yw2919~~
- ~~`transformSeg` - yw2919~~
- ~~`topology` - yw2919~~
- ~~`negXYPos` - yw2919~~
- `segmentIntersectsBoundingBoxCoordinates` -> `segmentIntersectsBoundingBox` - yw2919
- `Matrix` - yw2919
- `MTransformation` - yw2919
- `MInvTransformation` - yw2919
- `foldOverRISegments` - yw2919
- `findTransformation` - yw2919
- `wireToVertices` - yw2919
- `getTopLeftAndBottomRightCorner` - yw2919
- `segmentIntersectsBoundingBox` - yw2919
- `distanceFromPointToSegment` - yw2919
- `routeGivenWiresBasedOnPortPositions` - yw2919
- `getIntersectingSegments` - yw2919
- `getClosestSegment` - yw2919
- `getClickedSegment` - yw2919
- `checkSegmentAngle` - yw2919
- `getSafeDistanceForMove` - yw2919
- `moveSegment` - yw2919
- `init` - yw2919
- `filterWires` - yw2919
- `getConnectedWires` - yw2919
- `filterWiresByCompMoved` - yw2919
- `autorouteWire` - yw2919
- `revWire` - yw2919
- `partialAutoRoute` - yw2919
- `moveWire` - yw2919
- `updateWire` - yw2919

- `makeAllJumps` - gk518
- `updateWireSegmentJumps` - gk518
- `resetWireSegmentJumps` - gk518
- `updateWires` - gk518
- `update` - gk518
- `wireIntersectsBoundingBox` - gk518
- `getIntersectingWires` - gk518
- `getWireIfClicked` - gk518
- `pasteWires` - gk518
- `getPortIdsOfWires` - gk518



## Other Module Changes

* any changes made to other modules *

- Sheet.mDownUpdate - jam419
- Sheet.update - jam419
- DrawHelpers.MouseT + MouseButton - jam419
- Sheet.getWireBBox - yw2919




