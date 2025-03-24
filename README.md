# Idea for Application
Create a tic-tac-toe game with the abilities to  
1. Play against a friend by taking turns on a single device or against a bot with different difficulties
2. Play three in a row, four in a row, and five in a row varients as well as connect four.
3. Save games played and won to earn in game rewards
4. have in game music
# But how?
create a menu that's direction tree is:
- Play
  - Bot or local
     - three in a row
     - four in a row 
     - five in a row
     - connect four
- Music volume
- Cosmetics
 - backgrounds
   - X's
   - O's
# How the game would look like

<img width="481" alt="Menu" src="https://github.com/user-attachments/assets/3fae8206-59f1-47b4-a9ea-d49c8b528d41" />

<img width="725" alt="Screenshot 2025-03-12 at 12 29 27 PM" src="https://github.com/user-attachments/assets/abdba044-a02b-4f65-9ef4-0e9d72ee8ce7" />
<img width="728" alt="Screenshot 2025-03-17 at 11 29 52 AM" src="https://github.com/user-attachments/assets/850bca89-a39d-4a89-8b30-5f0692b5a6dc" />

[Uploading Untitled Diagram.drawio…]()<mxfile host="app.diagrams.net" agent="Mozilla/5.0 (X11; CrOS x86_64 14541.0.0) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/133.0.0.0 Safari/537.36" version="26.1.1">
  <diagram name="Page-1" id="go2jE-F7zgHgwCZpvS9J">
    <mxGraphModel dx="1612" dy="862" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="850" pageHeight="1100" math="0" shadow="0">
      <root>
        <mxCell id="0" />
        <mxCell id="1" parent="0" />
        <mxCell id="lA9IovG87rNFhPB63KIy-1" value="TicTacToe" style="swimlane;fontStyle=0;childLayout=stackLayout;horizontal=1;startSize=26;fillColor=none;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="160" y="130" width="140" height="104" as="geometry" />
        </mxCell>
        <mxCell id="lA9IovG87rNFhPB63KIy-2" value="-board:char" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="lA9IovG87rNFhPB63KIy-1">
          <mxGeometry y="26" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="lA9IovG87rNFhPB63KIy-3" value="-player2: Computer" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="lA9IovG87rNFhPB63KIy-1">
          <mxGeometry y="52" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="lA9IovG87rNFhPB63KIy-4" value="+takeOneTurn(): void" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="lA9IovG87rNFhPB63KIy-1">
          <mxGeometry y="78" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="lA9IovG87rNFhPB63KIy-5" value="Player" style="swimlane;fontStyle=0;childLayout=stackLayout;horizontal=1;startSize=26;fillColor=none;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="330" y="270" width="140" height="78" as="geometry" />
        </mxCell>
        <mxCell id="lA9IovG87rNFhPB63KIy-6" value="+ name: char" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="lA9IovG87rNFhPB63KIy-5">
          <mxGeometry y="26" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="lA9IovG87rNFhPB63KIy-7" value="+takeTurn(): void" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="lA9IovG87rNFhPB63KIy-5">
          <mxGeometry y="52" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="lA9IovG87rNFhPB63KIy-9" value="HumanPlayer" style="swimlane;fontStyle=0;childLayout=stackLayout;horizontal=1;startSize=26;fillColor=none;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="190" y="390" width="140" height="52" as="geometry" />
        </mxCell>
        <mxCell id="lA9IovG87rNFhPB63KIy-10" value="+takeTurn(): void" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="lA9IovG87rNFhPB63KIy-9">
          <mxGeometry y="26" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="lA9IovG87rNFhPB63KIy-13" value="Computer" style="swimlane;fontStyle=0;childLayout=stackLayout;horizontal=1;startSize=26;fillColor=none;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="500" y="390" width="140" height="52" as="geometry" />
        </mxCell>
        <mxCell id="lA9IovG87rNFhPB63KIy-16" value="+takeTurn(): void" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="lA9IovG87rNFhPB63KIy-13">
          <mxGeometry y="26" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="lA9IovG87rNFhPB63KIy-17" value="Classname" style="swimlane;fontStyle=1;align=center;verticalAlign=top;childLayout=stackLayout;horizontal=1;startSize=26;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="-90" y="240" width="160" height="130" as="geometry" />
        </mxCell>
        <mxCell id="lA9IovG87rNFhPB63KIy-18" value="-game: Tictactoe" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="lA9IovG87rNFhPB63KIy-17">
          <mxGeometry y="26" width="160" height="26" as="geometry" />
        </mxCell>
        <mxCell id="lA9IovG87rNFhPB63KIy-19" value="" style="line;strokeWidth=1;fillColor=none;align=left;verticalAlign=middle;spacingTop=-1;spacingLeft=3;spacingRight=3;rotatable=0;labelPosition=right;points=[];portConstraint=eastwest;strokeColor=inherit;" vertex="1" parent="lA9IovG87rNFhPB63KIy-17">
          <mxGeometry y="52" width="160" height="8" as="geometry" />
        </mxCell>
        <mxCell id="lA9IovG87rNFhPB63KIy-20" value="+ boarDisplay(): void&lt;div&gt;+placePiece(): void&lt;/div&gt;&lt;div&gt;+gameisDone(): void&lt;/div&gt;&lt;div&gt;+gameisDraw(): void&lt;/div&gt;" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="lA9IovG87rNFhPB63KIy-17">
          <mxGeometry y="60" width="160" height="70" as="geometry" />
        </mxCell>
        <mxCell id="lA9IovG87rNFhPB63KIy-21" value="Piece" style="swimlane;fontStyle=0;childLayout=stackLayout;horizontal=1;startSize=26;fillColor=none;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="-80" y="410" width="140" height="52" as="geometry" />
        </mxCell>
        <mxCell id="lA9IovG87rNFhPB63KIy-22" value="+symbol: char" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="lA9IovG87rNFhPB63KIy-21">
          <mxGeometry y="26" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="lA9IovG87rNFhPB63KIy-25" value="OPiece" style="swimlane;fontStyle=0;childLayout=stackLayout;horizontal=1;startSize=26;fillColor=none;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="30" y="492" width="140" height="52" as="geometry" />
        </mxCell>
        <mxCell id="lA9IovG87rNFhPB63KIy-26" value="+o: char" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="lA9IovG87rNFhPB63KIy-25">
          <mxGeometry y="26" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="lA9IovG87rNFhPB63KIy-27" value="XPiece" style="swimlane;fontStyle=0;childLayout=stackLayout;horizontal=1;startSize=30;fillColor=none;horizontalStack=0;resizeParent=1;resizeParentMax=0;resizeLast=0;collapsible=1;marginBottom=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="-210" y="490" width="140" height="56" as="geometry" />
        </mxCell>
        <mxCell id="lA9IovG87rNFhPB63KIy-28" value="+x: char" style="text;strokeColor=none;fillColor=none;align=left;verticalAlign=top;spacingLeft=4;spacingRight=4;overflow=hidden;rotatable=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;whiteSpace=wrap;html=1;" vertex="1" parent="lA9IovG87rNFhPB63KIy-27">
          <mxGeometry y="30" width="140" height="26" as="geometry" />
        </mxCell>
        <mxCell id="lA9IovG87rNFhPB63KIy-29" value="" style="endArrow=classic;html=1;rounded=0;exitX=0.5;exitY=0;exitDx=0;exitDy=0;entryX=0;entryY=0.25;entryDx=0;entryDy=0;" edge="1" parent="1" source="lA9IovG87rNFhPB63KIy-17" target="lA9IovG87rNFhPB63KIy-1">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="230" y="430" as="sourcePoint" />
            <mxPoint x="120" y="80" as="targetPoint" />
            <Array as="points">
              <mxPoint x="-10" y="160" />
              <mxPoint x="160" y="160" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="lA9IovG87rNFhPB63KIy-30" value="" style="endArrow=classic;html=1;rounded=0;entryX=0.436;entryY=1.026;entryDx=0;entryDy=0;entryPerimeter=0;" edge="1" parent="1" target="lA9IovG87rNFhPB63KIy-20">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="-20" y="410" as="sourcePoint" />
            <mxPoint x="30" y="360" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="lA9IovG87rNFhPB63KIy-31" value="" style="endArrow=classic;startArrow=classic;html=1;rounded=0;" edge="1" parent="1" target="lA9IovG87rNFhPB63KIy-22">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="-150" y="492" as="sourcePoint" />
            <mxPoint x="-100" y="442" as="targetPoint" />
            <Array as="points">
              <mxPoint x="-150" y="450" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="lA9IovG87rNFhPB63KIy-33" value="" style="endArrow=classic;html=1;rounded=0;entryX=1.001;entryY=-0.011;entryDx=0;entryDy=0;entryPerimeter=0;" edge="1" parent="1" target="lA9IovG87rNFhPB63KIy-22">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="100" y="490" as="sourcePoint" />
            <mxPoint x="90" y="430" as="targetPoint" />
            <Array as="points">
              <mxPoint x="100" y="436" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="lA9IovG87rNFhPB63KIy-34" value="" style="endArrow=classic;html=1;rounded=0;entryX=1.023;entryY=0.207;entryDx=0;entryDy=0;entryPerimeter=0;" edge="1" parent="1" target="lA9IovG87rNFhPB63KIy-2">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="400" y="270" as="sourcePoint" />
            <mxPoint x="370" y="190" as="targetPoint" />
            <Array as="points">
              <mxPoint x="400" y="160" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="lA9IovG87rNFhPB63KIy-35" value="" style="endArrow=classic;html=1;rounded=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;exitX=0.348;exitY=-0.044;exitDx=0;exitDy=0;exitPerimeter=0;" edge="1" parent="1" source="lA9IovG87rNFhPB63KIy-9" target="lA9IovG87rNFhPB63KIy-6">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="250" y="390" as="sourcePoint" />
            <mxPoint x="300" y="340" as="targetPoint" />
            <Array as="points">
              <mxPoint x="240" y="310" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="lA9IovG87rNFhPB63KIy-36" value="" style="endArrow=classic;html=1;rounded=0;entryX=1.017;entryY=0.156;entryDx=0;entryDy=0;entryPerimeter=0;exitX=0.429;exitY=0;exitDx=0;exitDy=0;exitPerimeter=0;" edge="1" parent="1" source="lA9IovG87rNFhPB63KIy-13" target="lA9IovG87rNFhPB63KIy-6">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="560" y="370" as="sourcePoint" />
            <mxPoint x="610" y="320" as="targetPoint" />
            <Array as="points">
              <mxPoint x="560" y="300" />
            </Array>
          </mxGeometry>
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>



<img width="735" alt="Screenshot 2025-03-17 at 11 40 21 AM" src="https://github.com/user-attachments/assets/0635856f-e273-4dfa-9bdb-dbc5b6d928ca" />

