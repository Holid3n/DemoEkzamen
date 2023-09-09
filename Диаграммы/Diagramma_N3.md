<mxfile host="app.diagrams.net" modified="2023-09-09T11:17:54.903Z" agent="Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/114.0.0.0 YaBrowser/23.7.4.971 Yowser/2.5 Safari/537.36" etag="zI42KmhOwSUaKx2vWg3n" version="21.7.4" type="device">
  <diagram name="Страница — 1" id="mMhL_vUVwXyliONr3Lp2">
    <mxGraphModel dx="1540" dy="890" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="827" pageHeight="1169" math="0" shadow="0">
      <root>
        <mxCell id="0" />
        <mxCell id="1" parent="0" />
        <mxCell id="E2L1ffQVjtBInnkE9SzP-2" value="Диаграмма выполнения упражнений на день" style="shape=table;childLayout=tableLayout;startSize=40;collapsible=0;recursiveResize=0;expand=0;fontSize=16;fillColor=#008a00;strokeColor=#005700;fontColor=#ffffff;" parent="1" vertex="1">
          <mxGeometry x="200" y="90" width="962" height="770" as="geometry" />
        </mxCell>
        <mxCell id="E2L1ffQVjtBInnkE9SzP-3" value="" style="shape=tableRow;horizontal=0;swimlaneHead=0;swimlaneBody=0;top=0;left=0;strokeColor=inherit;bottom=0;right=0;dropTarget=0;fontStyle=0;fillColor=none;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;startSize=0;collapsible=0;recursiveResize=0;expand=0;fontSize=16;" parent="E2L1ffQVjtBInnkE9SzP-2" vertex="1">
          <mxGeometry y="40" width="962" height="730" as="geometry" />
        </mxCell>
        <mxCell id="E2L1ffQVjtBInnkE9SzP-4" value="Система" style="swimlane;swimlaneHead=0;swimlaneBody=0;fontStyle=0;strokeColor=#005700;connectable=0;fillColor=#008a00;startSize=50;collapsible=0;recursiveResize=0;expand=0;fontSize=16;fontColor=#ffffff;" parent="E2L1ffQVjtBInnkE9SzP-3" vertex="1">
          <mxGeometry width="405" height="730" as="geometry">
            <mxRectangle width="405" height="730" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="E2L1ffQVjtBInnkE9SzP-17" value="Вывести список упражнений на день" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#008a00;strokeColor=#005700;fontColor=#ffffff;" parent="E2L1ffQVjtBInnkE9SzP-4" vertex="1">
          <mxGeometry x="70" y="130" width="250" height="40" as="geometry" />
        </mxCell>
        <mxCell id="E2L1ffQVjtBInnkE9SzP-26" value="Отобразить информацию об упражнении" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#008a00;strokeColor=#005700;fontColor=#ffffff;" parent="E2L1ffQVjtBInnkE9SzP-4" vertex="1">
          <mxGeometry x="20" y="330" width="260" height="50" as="geometry" />
        </mxCell>
        <mxCell id="E2L1ffQVjtBInnkE9SzP-5" value="Клиент" style="swimlane;swimlaneHead=0;swimlaneBody=0;fontStyle=0;strokeColor=#005700;connectable=0;fillColor=#008a00;startSize=50;collapsible=0;recursiveResize=0;expand=0;fontSize=16;fontColor=#ffffff;" parent="E2L1ffQVjtBInnkE9SzP-3" vertex="1">
          <mxGeometry x="405" width="535" height="730" as="geometry">
            <mxRectangle width="535" height="730" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="E2L1ffQVjtBInnkE9SzP-16" value="" style="ellipse;whiteSpace=wrap;html=1;aspect=fixed;fillColor=#0050ef;strokeColor=#001DBC;fontColor=#ffffff;" parent="E2L1ffQVjtBInnkE9SzP-5" vertex="1">
          <mxGeometry x="224" y="60" width="60" height="60" as="geometry" />
        </mxCell>
        <mxCell id="E2L1ffQVjtBInnkE9SzP-24" value="Нет упражнения" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" parent="E2L1ffQVjtBInnkE9SzP-5" source="E2L1ffQVjtBInnkE9SzP-19" target="E2L1ffQVjtBInnkE9SzP-22" edge="1">
          <mxGeometry relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="105" y="225" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="E2L1ffQVjtBInnkE9SzP-25" value="Есть упражнение для выполнения" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.53;entryY=-0.15;entryDx=0;entryDy=0;entryPerimeter=0;" parent="E2L1ffQVjtBInnkE9SzP-5" source="E2L1ffQVjtBInnkE9SzP-19" target="E2L1ffQVjtBInnkE9SzP-23" edge="1">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="E2L1ffQVjtBInnkE9SzP-19" value="" style="rhombus;whiteSpace=wrap;html=1;fillColor=#0050ef;strokeColor=#001DBC;fontColor=#ffffff;" parent="E2L1ffQVjtBInnkE9SzP-5" vertex="1">
          <mxGeometry x="215" y="190" width="68" height="70" as="geometry" />
        </mxCell>
        <mxCell id="E2L1ffQVjtBInnkE9SzP-21" value="Есть упражнения для выполнения ?" style="text;html=1;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;whiteSpace=wrap;rounded=0;" parent="E2L1ffQVjtBInnkE9SzP-5" vertex="1">
          <mxGeometry x="145" y="260" width="214" height="30" as="geometry" />
        </mxCell>
        <mxCell id="E2L1ffQVjtBInnkE9SzP-22" value="" style="ellipse;whiteSpace=wrap;html=1;aspect=fixed;fillColor=#647687;fontColor=#ffffff;strokeColor=#314354;" parent="E2L1ffQVjtBInnkE9SzP-5" vertex="1">
          <mxGeometry x="75" y="240" width="50" height="50" as="geometry" />
        </mxCell>
        <mxCell id="E2L1ffQVjtBInnkE9SzP-23" value="Выбрать Упражнение" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#008a00;strokeColor=#005700;fontColor=#ffffff;" parent="E2L1ffQVjtBInnkE9SzP-5" vertex="1">
          <mxGeometry x="375" y="280" width="100" height="40" as="geometry" />
        </mxCell>
        <mxCell id="E2L1ffQVjtBInnkE9SzP-27" value="Пропустить упражнение" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#008a00;strokeColor=#005700;fontColor=#ffffff;" parent="E2L1ffQVjtBInnkE9SzP-5" vertex="1">
          <mxGeometry x="21" y="490" width="148" height="40" as="geometry" />
        </mxCell>
        <mxCell id="E2L1ffQVjtBInnkE9SzP-31" value="Не выполнил" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.5;entryY=0;entryDx=0;entryDy=0;exitX=0;exitY=0.5;exitDx=0;exitDy=0;" parent="E2L1ffQVjtBInnkE9SzP-5" source="E2L1ffQVjtBInnkE9SzP-28" target="E2L1ffQVjtBInnkE9SzP-27" edge="1">
          <mxGeometry x="0.8182" y="1" relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="199" y="370" />
              <mxPoint x="94" y="370" />
              <mxPoint x="94" y="490" />
            </Array>
            <mxPoint x="247" y="330" as="sourcePoint" />
            <mxPoint x="84.00000000000023" y="420" as="targetPoint" />
            <mxPoint as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="E2L1ffQVjtBInnkE9SzP-50" value="Выполнил" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" parent="E2L1ffQVjtBInnkE9SzP-5" source="E2L1ffQVjtBInnkE9SzP-28" target="E2L1ffQVjtBInnkE9SzP-45" edge="1">
          <mxGeometry x="0.4215" y="-1" relative="1" as="geometry">
            <mxPoint as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="E2L1ffQVjtBInnkE9SzP-28" value="" style="rhombus;whiteSpace=wrap;html=1;fillColor=#0050ef;strokeColor=#001DBC;fontColor=#ffffff;" parent="E2L1ffQVjtBInnkE9SzP-5" vertex="1">
          <mxGeometry x="199" y="330" width="70" height="70" as="geometry" />
        </mxCell>
        <mxCell id="E2L1ffQVjtBInnkE9SzP-44" value="Клиент выполнил упражнение?" style="text;html=1;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;whiteSpace=wrap;rounded=0;" parent="E2L1ffQVjtBInnkE9SzP-5" vertex="1">
          <mxGeometry x="139.5" y="400" width="189" height="30" as="geometry" />
        </mxCell>
        <mxCell id="E2L1ffQVjtBInnkE9SzP-51" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.826;entryY=-0.075;entryDx=0;entryDy=0;entryPerimeter=0;" parent="E2L1ffQVjtBInnkE9SzP-5" source="E2L1ffQVjtBInnkE9SzP-45" target="E2L1ffQVjtBInnkE9SzP-49" edge="1">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="E2L1ffQVjtBInnkE9SzP-52" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" parent="E2L1ffQVjtBInnkE9SzP-5" source="E2L1ffQVjtBInnkE9SzP-45" target="E2L1ffQVjtBInnkE9SzP-47" edge="1">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="E2L1ffQVjtBInnkE9SzP-45" value="" style="rounded=0;whiteSpace=wrap;html=1;fillColor=#1ba1e2;strokeColor=#006EAF;fontColor=#ffffff;" parent="E2L1ffQVjtBInnkE9SzP-5" vertex="1">
          <mxGeometry x="276" y="540" width="120" height="30" as="geometry" />
        </mxCell>
        <mxCell id="E2L1ffQVjtBInnkE9SzP-46" value="" style="rounded=0;whiteSpace=wrap;html=1;fillColor=#1ba1e2;strokeColor=#006EAF;fontColor=#ffffff;" parent="E2L1ffQVjtBInnkE9SzP-5" vertex="1">
          <mxGeometry x="276" y="680" width="120" height="30" as="geometry" />
        </mxCell>
        <mxCell id="E2L1ffQVjtBInnkE9SzP-53" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0;entryY=0.75;entryDx=0;entryDy=0;" parent="E2L1ffQVjtBInnkE9SzP-5" source="E2L1ffQVjtBInnkE9SzP-47" target="E2L1ffQVjtBInnkE9SzP-46" edge="1">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="E2L1ffQVjtBInnkE9SzP-47" value="Изменит статус выполнения упражнения" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#008a00;fontColor=#ffffff;strokeColor=#005700;" parent="E2L1ffQVjtBInnkE9SzP-5" vertex="1">
          <mxGeometry x="146" y="600" width="138" height="40" as="geometry" />
        </mxCell>
        <mxCell id="E2L1ffQVjtBInnkE9SzP-54" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=1.008;entryY=1.233;entryDx=0;entryDy=0;entryPerimeter=0;" parent="E2L1ffQVjtBInnkE9SzP-5" source="E2L1ffQVjtBInnkE9SzP-49" target="E2L1ffQVjtBInnkE9SzP-46" edge="1">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="E2L1ffQVjtBInnkE9SzP-49" value="Ввести данные о пульсе" style="rounded=1;whiteSpace=wrap;html=1;fillColor=#008a00;fontColor=#ffffff;strokeColor=#005700;" parent="E2L1ffQVjtBInnkE9SzP-5" vertex="1">
          <mxGeometry x="376" y="610" width="138" height="40" as="geometry" />
        </mxCell>
        <mxCell id="E2L1ffQVjtBInnkE9SzP-6" value="" style="swimlane;swimlaneHead=0;swimlaneBody=0;fontStyle=0;strokeColor=inherit;connectable=1;fillColor=none;startSize=50;collapsible=0;recursiveResize=0;expand=0;fontSize=16;movable=1;resizable=1;rotatable=1;deletable=1;editable=1;locked=0;" parent="E2L1ffQVjtBInnkE9SzP-3" vertex="1">
          <mxGeometry x="940" width="22" height="730" as="geometry">
            <mxRectangle width="22" height="730" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="E2L1ffQVjtBInnkE9SzP-18" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.532;entryY=0.075;entryDx=0;entryDy=0;entryPerimeter=0;" parent="E2L1ffQVjtBInnkE9SzP-3" source="E2L1ffQVjtBInnkE9SzP-16" target="E2L1ffQVjtBInnkE9SzP-17" edge="1">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="E2L1ffQVjtBInnkE9SzP-20" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" parent="E2L1ffQVjtBInnkE9SzP-3" source="E2L1ffQVjtBInnkE9SzP-17" target="E2L1ffQVjtBInnkE9SzP-19" edge="1">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="E2L1ffQVjtBInnkE9SzP-29" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" parent="E2L1ffQVjtBInnkE9SzP-3" source="E2L1ffQVjtBInnkE9SzP-23" target="E2L1ffQVjtBInnkE9SzP-26" edge="1">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="E2L1ffQVjtBInnkE9SzP-30" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" parent="E2L1ffQVjtBInnkE9SzP-3" source="E2L1ffQVjtBInnkE9SzP-26" target="E2L1ffQVjtBInnkE9SzP-28" edge="1">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
