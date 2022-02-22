# Team members


| Name             | IC user | github login |
| --------------   | ------- | ------------ |
| Simon Staal      | sts219  | sts219       |
| Petra Ratkai     | pr2518  | petraratkai  |
| Nathan Hamill    | nh1019  | nh1019       |
| Jiah Yuee Chin   | jyc119  | jyc119       |
| Kaius Conway-Lai | kc319   | kc319        |
| A.N.Other        | login2  | login2gh     |

# Individual Contributions

Write down every top-level function, in its initial order in files, and who is responsible for it, on a single line (line numbers are unstable). Give team members as IC logins Add changes in section below

## Symbol

**1 - jyc119, kc319**

- posDiff
- posAdd
- posOf
- title
- bustitle
- prefix
- gateDecoderType
- portDecName
- portLists
- roundToN
- customToLength
- makeComp
- createNewSymbol
- addToPortModel
- getPortPosEdgeGap
- getPortPos
- getPortPosModel
- addText
- portCircles
- portText
- drawPortsText
- drawPorts
- createPolygon
- createBiColorPolygon
- addInvertor
- addClock
- addHorizontalLine
- outlineColor
- addHorizontalColorLine
- compSymbol
- init
- renderSymbol
- MapsIntoLists
- view

**2 - pr2518**

- getBoundingBoxofSymbol
- getBoundingBoxes
- getOneBoundingBox
- getSymbolPos
- getInputPortsPositionMap
- getOutputPortsPositionMap
- getPort
- getPortLocations
- getInputPortLocation
- getOutputPortLocation
- getOnePortLocation
- getOnePortLocationNew
- getTwoPortLocations
- getCopiedSymbols
- filterString
- regex
- getCompList
- getIndex
- labelGenNumber
- generateLabel
- pasteSymbols
- getEquivalentCopiedPorts
- addSymbol
- changeNumberOfBitsf
- changeLsbf
- changeConstantf
- update
- extractComponent
- extractComponents

### Symbol Changes

20 Feb dfun --> tomcl
22 Feb bfun --> login2

_listing changes here as they happen_

- List anything special here about who did what if needed\*

## Buswire

**Debugging - stst219**

- ppSId
- ppS
- ppWId
- ppMaps
- ppSeg
- pp

**1 - **

**2 - sts219**

- segmentIntersectsSegmentCoordinates
- getTopLeftAndBottomRightCorner
- segmentIntersectsBoundingBoxCoordinates
- distanceFromPointToSegment
- routeGivenWiresBasedOnPortPositions
- getIntersectingSegments
- getClosestSegment
- getClickedSegment
- checkSegmentAngle
- segPointsLeft
- segXDelta
- moveXJoinPos
- changeLengths
- getSafeDistanceForMove
- removeRedundantSegments
- moveSegment
- init
- getConnectedWires
- filterWiresByCompMoved
- autorouteWire
- revSegments
- addPosPos
- moveEnd
- moveStart
- moveAll
- transformXY
- transformSeg
- topology
- partialAutoRoute
- negXYPos
- moveWire
- updateWire

**3 - nh1019**

- makeAllJumps
- updateWireSegmentJumps
- resetWireSegmentJumps
- updateWires
- update
- wireIntersectsBoundingBox
- getIntersectingWires
- getWireIfClicked
- pasteWires
- portIdsOfWires

### Buswire changes
21/02 foldOverSegs -> sts219
21/02 wireIntersectsBoundingBox -> sts219

## Other Module Changes

- any changes made to other modules \*

Sheet.interfacefun - tomcl
