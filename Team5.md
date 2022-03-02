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

- `posDiff` - rv519
- `posAdd` - rv519
~~- `posOf` - rv519~~
- **New** `rotatePorts` - rv519
- `addText` - rv519
~~- `title` - rv519~~
- `busTitle` -> `getbusTitle` - rv519
- `prefix` -> `getSymbolLabel` - rv519
- `gateDecoderType` -> `getSymbolTitle` - rv519
- `portDecName` -> `getSymbolPortsTitle` - rv519
~~- `portList` - rv519~~
~~- `customToLength` - rv519~~
- `makeComp` -> `createNewComponent` - rv519
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
- `posDiff` - mt1819
- `posAdd` - mt1819
- `posOf` - mt1819
- `symbolTitle` - mt1819
- `busTitle` - mt1819
- `prefix` - mt1819
- `gateDecoderType` - mt1819
- `portDecName` - mt1819
- `portList` - mt1819
- `customToLength` - mt1819
- `makeComp` - mt1819
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

2 March rv519 -> Refactoring and removed several functions including `MapsIntoLists`, `outlineColor`, `addHorizontalLine`, `createBiColorPolygon`, `createPolygon`, `portCircles`, `getPortPosModel`, `getPortPosEdgeGap`, `customToLength`, `portList`, `title`, `posOf`. Additionally renamed and added functions as above. 

## Buswire

- `convertRISegsToVertices` - yz8819
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

- `segmentIntersectsSegmentCoordinates` - yw2918
- `getTopLeftAndBottomRightCorner` - yw2918
- `segmentIntersectsBoundingBoxCoordinates` - yw2918
- `distanceFromPointToSegment` - yw2918
- `routeGivenWiresBasedOnPortPositions` - yw2918
- `getIntersectingSegments` - yw2918
- `getClosestSegment` - yw2918
- `getClickedSegment` - yw2918
- `checkSegmentAngle` - yw2918
- `segPointsLeft` - yw2918
- `segXDelta` - yw2918
- `moveXJoinPos` - yw2918
- `changeLengths` - yw2918
- `getSafeDistanceForMove` - yw2918
- `removeRedundantSegments` - yw2918
- `moveSegment` - yw2918
- `init` - yw2918
- `getConnectedWires` - yw2918
- `filterWiresByCompMoved` - yw2918
- `autorouteWire` - yw2918
- `revSegments` - yw2918
- `addPosPos` - yw2918
- `moveEnd` - yw2918
- `moveStart` - yw2918
- `moveAll` - yw2918
- `transformXY` - yw2918
- `transformSeg` - yw2918
- `topology` - yw2918
- `partialAutoRoute` - yw2918
- `negXYPos` - yw2918
- `moveWire` - yw2918
- `updateWire` - yw2918

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
- Sheet.update - rv519
- type KeyboardMsg - rv519



