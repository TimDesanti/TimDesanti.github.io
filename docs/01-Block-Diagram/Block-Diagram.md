[Individual Block EGR304 TND (1).drawio](https://github.com/user-attachments/files/23535898/Individual.Block.EGR304.TND.1.drawio)[Individual Block EGR304 TND (1).drawio](https://github.com/user-attachments/files/23535889/Individual.Block.EGR304.TND.1.drawio)[Individual Block EGR304 TND (1).drawio](https://github.com/user-attachments/files/23535882/Individual.Block.EGR304.TND.1.drawio)---
title: Individual Block Diagram for Slat Motor
tags: 
- tag1
- tag2
---

## Overview
This block diagram illustrates the system architecture for controlling a DC motor using the Microchip PIC18F57Q43 Curiosity Nano board. It shows how power, sensing, and actuation are distributed throughout the system. A 12V 3A unregulated power supply provides the main power, which is regulated to 12V (1.5A) for the microcontroller and control electronics. An analog sensor connected to the ADC input (RA0) provides input signals for feedback or control. The H-Bridge (FAN8100N) drives the motor (actuator) using PWM signals from the microcontroller. Green LED to check if power is going through the system. It translates to a motor that will open and close the blinds depending on the signals given from the other components.


## Motor PCB Block Diagram 


<img width="742" height="901" alt="Individual Block EGR304 TND drawio (3)" src="https://github.com/user-attachments/assets/21aac557-e95a-48ab-957c-cf9555615091" />





[Individual Block EGR304 TND (1).drawio](https://github.com/user-attachments/files/23535902/Individual.Block.EGR304.TND.1.drawio)
<mxfile host="app.diagrams.net" agent="Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/142.0.0.0 Safari/537.36 Edg/142.0.0.0" version="29.0.2">
  <diagram name="Page-1" id="ePI6UXHfgp6yXxjbnx8W">
    <mxGraphModel grid="1" page="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" pageScale="1" pageWidth="850" pageHeight="1100" math="0" shadow="0">
      <root>
        <mxCell id="0" />
        <mxCell id="1" parent="0" />
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-1" value="&lt;p style=&quot;line-height: 120%&quot;&gt;5V unregulated&lt;/p&gt;&lt;p style=&quot;line-height: 120%&quot;&gt;&amp;nbsp;power supply&lt;/p&gt;" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="-340" y="-440" width="120" height="70" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-34" value="" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="-370" y="-310" width="740" height="660" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-35" value="Microchip PIC18F57Q43 Curiosity Nano" style="rounded=0;whiteSpace=wrap;html=1;verticalAlign=top;fillColor=none;movable=1;resizable=1;rotatable=1;deletable=1;editable=1;locked=0;connectable=1;" vertex="1" parent="1">
          <mxGeometry x="-150" y="-300" width="260" height="250" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-36" value="&lt;div&gt;&lt;span&gt;H-Bridge&lt;/span&gt;&lt;/div&gt;&lt;div&gt;&lt;span style=&quot;background-color: rgb(255, 255, 102);&quot;&gt;Adafruit Industries LLC&lt;/span&gt;&lt;/div&gt;&lt;div&gt;4489&lt;/div&gt;" style="rounded=0;whiteSpace=wrap;html=1;labelBackgroundColor=none;" vertex="1" parent="1">
          <mxGeometry x="210" y="70" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-37" style="edgeStyle=none;curved=1;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0;exitY=0.5;exitDx=0;exitDy=0;fontSize=12;startSize=8;endSize=8;" edge="1" parent="1">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="-180" y="-165" as="sourcePoint" />
            <mxPoint x="-180" y="-165" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-38" style="edgeStyle=none;curved=1;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.75;exitY=0;exitDx=0;exitDy=0;fontSize=12;startSize=8;endSize=8;" edge="1" parent="1">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="177.5" y="-195" as="sourcePoint" />
            <mxPoint x="177.5" y="-195" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-40" value="PWM" style="rounded=0;whiteSpace=wrap;html=1;align=left;fillColor=none;" vertex="1" parent="1">
          <mxGeometry x="30" y="-270" width="80" height="50" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-41" value="PWM" style="rounded=0;whiteSpace=wrap;html=1;align=left;fillColor=none;" vertex="1" parent="1">
          <mxGeometry x="30" y="-220" width="80" height="50" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-42" value="PWM" style="rounded=0;whiteSpace=wrap;html=1;align=left;fillColor=none;" vertex="1" parent="1">
          <mxGeometry x="30" y="-170" width="80" height="50" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-43" value="ADC1" style="rounded=0;whiteSpace=wrap;html=1;align=right;" vertex="1" parent="1">
          <mxGeometry x="-150" y="-250" width="80" height="50" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-44" value="RA0" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="-150" y="-240" width="40" height="30" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-45" value="RA1" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="70" y="-260" width="40" height="30" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-46" value="Digital I/O" style="rounded=0;whiteSpace=wrap;html=1;fillColor=none;verticalAlign=top;" vertex="1" parent="1">
          <mxGeometry x="-140" y="-110" width="230" height="60" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-47" value="RC4" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="-130" y="-80" width="40" height="30" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-48" value="RC5" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="-90" y="-80" width="40" height="30" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-49" value="RC1" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="-50" y="-80" width="40" height="30" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-50" value="" style="rounded=0;whiteSpace=wrap;html=1;labelBackgroundColor=none;" vertex="1" parent="1">
          <mxGeometry x="-10" y="-80" width="40" height="30" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-51" value="" style="rounded=0;whiteSpace=wrap;html=1;labelBackgroundColor=none;" vertex="1" parent="1">
          <mxGeometry x="30" y="-80" width="40" height="30" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-52" value="&lt;div&gt;&lt;span&gt;Motor DC&lt;/span&gt;&lt;/div&gt;&lt;div&gt;&lt;span style=&quot;background-color: rgb(255, 255, 153);&quot;&gt;Pololu&lt;/span&gt;&lt;/div&gt;&lt;div&gt;&lt;span&gt;3045&lt;/span&gt;&lt;/div&gt;" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="210" y="190" width="100" height="50" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-53" value="GN&lt;span style=&quot;color: rgba(0, 0, 0, 0); font-family: monospace; font-size: 0px; text-align: start; text-wrap-mode: nowrap;&quot;&gt;%3CmxGraphModel%3E%3Croot%3E%3CmxCell%20id%3D%220%22%2F%3E%3CmxCell%20id%3D%221%22%20parent%3D%220%22%2F%3E%3CmxCell%20id%3D%222%22%20value%3D%22%22%20style%3D%22endArrow%3Dclassic%3BstartArrow%3Dclassic%3Bhtml%3D1%3Brounded%3D0%3BexitX%3D0.5%3BexitY%3D0%3BexitDx%3D0%3BexitDy%3D0%3BentryX%3D0.5%3BentryY%3D1%3BentryDx%3D0%3BentryDy%3D0%3B%22%20edge%3D%221%22%20parent%3D%221%22%3E%3CmxGeometry%20width%3D%2250%22%20height%3D%2250%22%20relative%3D%221%22%20as%3D%22geometry%22%3E%3CmxPoint%20x%3D%221120%22%20y%3D%22730%22%20as%3D%22sourcePoint%22%2F%3E%3CmxPoint%20x%3D%221115%22%20y%3D%22700%22%20as%3D%22targetPoint%22%2F%3E%3C%2FmxGeometry%3E%3C%2FmxCell%3E%3C%2Froot%3E%3C%2FmxGraphModel%3E&lt;/span&gt;D" style="whiteSpace=wrap;html=1;aspect=fixed;" vertex="1" parent="1">
          <mxGeometry x="-110" y="240" width="30" height="30" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-54" value="RF7" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="70" y="-210" width="40" height="30" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-55" value="RF6" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="70" y="-160" width="40" height="30" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-56" value="DAC1" style="rounded=0;whiteSpace=wrap;html=1;align=right;" vertex="1" parent="1">
          <mxGeometry x="-150" y="-180" width="80" height="50" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-57" value="&lt;span style=&quot;background-color: rgb(255, 255, 51);&quot;&gt;RA2&lt;/span&gt;" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="-150" y="-170" width="40" height="30" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-58" value="&lt;div&gt;Green&lt;span style=&quot;background-color: transparent; color: light-dark(rgb(0, 0, 0), rgb(255, 255, 255));&quot;&gt;&amp;nbsp;LED&lt;/span&gt;&lt;/div&gt;" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="240" y="-260" width="60" height="30" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-59" value="&lt;div&gt;&lt;font style=&quot;font-size: 11px;&quot;&gt;digital/parallel&lt;/font&gt;&lt;/div&gt;&lt;div&gt;&lt;font size=&quot;3&quot;&gt;(5V,&amp;nbsp;1 Pin)&lt;/font&gt;&lt;/div&gt;" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=1;exitY=0.5;exitDx=0;exitDy=0;entryX=-0.003;entryY=0.115;entryDx=0;entryDy=0;fontSize=8;entryPerimeter=0;" edge="1" parent="1" target="Jj-Pi44mvM_tSbgrSIMR-36">
          <mxGeometry relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="180" y="-190" />
              <mxPoint x="180" y="76" />
            </Array>
            <mxPoint x="110" y="-190" as="sourcePoint" />
            <mxPoint x="205" y="76" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-60" value="&lt;div&gt;&lt;font style=&quot;font-size: 11px;&quot;&gt;digital/parallel&lt;/font&gt;&lt;/div&gt;&lt;div&gt;&lt;font size=&quot;3&quot;&gt;(5V,&amp;nbsp;1 Pin)&lt;/font&gt;&lt;/div&gt;" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=1;exitY=0.5;exitDx=0;exitDy=0;fontSize=8;entryX=0.012;entryY=0.596;entryDx=0;entryDy=0;entryPerimeter=0;" edge="1" parent="1">
          <mxGeometry relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="138.82999999999993" y="-140" />
              <mxPoint x="138.82999999999993" y="100" />
              <mxPoint x="198.82999999999993" y="100" />
              <mxPoint x="198.82999999999993" y="101" />
            </Array>
            <mxPoint x="108.82999999999993" y="-140" as="sourcePoint" />
            <mxPoint x="209.9995200000003" y="101.21252000000004" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-62" value="&lt;div&gt;&lt;font style=&quot;font-size: 12px;&quot;&gt;digital/parallel&lt;/font&gt;&lt;/div&gt;&lt;div&gt;&lt;font size=&quot;3&quot;&gt;(5V,&amp;nbsp;1 Pin&lt;/font&gt;&lt;span style=&quot;font-size: medium; background-color: light-dark(#ffffff, var(--ge-dark-color, #121212)); color: light-dark(rgb(0, 0, 0), rgb(255, 255, 255));&quot;&gt;)&lt;/span&gt;&lt;/div&gt;" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=1;exitY=0.25;exitDx=0;exitDy=0;entryX=0;entryY=0.25;entryDx=0;entryDy=0;fontSize=8;" edge="1" parent="1" source="Jj-Pi44mvM_tSbgrSIMR-35" target="Jj-Pi44mvM_tSbgrSIMR-58">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="160" y="-250" as="sourcePoint" />
            <mxPoint x="235" y="-250" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-63" value="" style="group" connectable="0" vertex="1" parent="1">
          <mxGeometry x="-250" y="290" width="160" height="60" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-64" value="connector 1" style="rounded=0;whiteSpace=wrap;html=1;verticalAlign=bottom;" vertex="1" parent="Jj-Pi44mvM_tSbgrSIMR-63">
          <mxGeometry width="160" height="60" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-65" value="digital" style="rounded=0;whiteSpace=wrap;html=1;verticalAlign=bottom;" vertex="1" parent="Jj-Pi44mvM_tSbgrSIMR-63">
          <mxGeometry y="20" width="100" height="20" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-66" value="analog" style="rounded=0;whiteSpace=wrap;html=1;verticalAlign=bottom;" vertex="1" parent="Jj-Pi44mvM_tSbgrSIMR-63">
          <mxGeometry x="100" y="20" width="40" height="20" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-67" value="1" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="Jj-Pi44mvM_tSbgrSIMR-63">
          <mxGeometry width="20" height="20" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-68" value="2" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="Jj-Pi44mvM_tSbgrSIMR-63">
          <mxGeometry x="20" width="20" height="20" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-69" value="3" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="Jj-Pi44mvM_tSbgrSIMR-63">
          <mxGeometry x="40" width="20" height="20" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-70" value="4" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="Jj-Pi44mvM_tSbgrSIMR-63">
          <mxGeometry x="60" width="20" height="20" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-71" value="5" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="Jj-Pi44mvM_tSbgrSIMR-63">
          <mxGeometry x="80" width="20" height="20" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-72" value="6" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="Jj-Pi44mvM_tSbgrSIMR-63">
          <mxGeometry x="100" width="20" height="20" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-73" value="7" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="Jj-Pi44mvM_tSbgrSIMR-63">
          <mxGeometry x="120" width="20" height="20" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-74" value="8" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="Jj-Pi44mvM_tSbgrSIMR-63">
          <mxGeometry x="140" width="20" height="20" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-75" value="&lt;div&gt;&lt;font style=&quot;font-size: 12px;&quot;&gt;digital/parallel&lt;/font&gt;&lt;/div&gt;&lt;div&gt;&lt;font size=&quot;3&quot;&gt;(12V, 2 Pins)&lt;/font&gt;&lt;/div&gt;" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=1;exitDx=0;exitDy=0;entryX=0.5;entryY=0;entryDx=0;entryDy=0;fontSize=8;" edge="1" parent="1">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="240" y="130" as="sourcePoint" />
            <mxPoint x="240" y="192" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-76" value="" style="endArrow=classic;html=1;rounded=0;exitX=0.5;exitY=0;exitDx=0;exitDy=0;entryX=0.5;entryY=1;entryDx=0;entryDy=0;" edge="1" parent="1" source="Jj-Pi44mvM_tSbgrSIMR-74" target="Jj-Pi44mvM_tSbgrSIMR-53">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="-10" y="280" as="sourcePoint" />
            <mxPoint y="270" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-77" value="" style="endArrow=classic;html=1;rounded=0;entryX=0.3;entryY=1.008;entryDx=0;entryDy=0;entryPerimeter=0;exitX=0.5;exitY=0;exitDx=0;exitDy=0;" edge="1" parent="1" source="Jj-Pi44mvM_tSbgrSIMR-68" target="Jj-Pi44mvM_tSbgrSIMR-35">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="-230" y="290" as="sourcePoint" />
            <mxPoint x="-73" as="targetPoint" />
            <Array as="points">
              <mxPoint x="-220" y="200" />
              <mxPoint x="-80" y="200" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-78" value="&lt;div style=&quot;&quot;&gt;&lt;font style=&quot;font-size: 12px;&quot;&gt;digital/parallel&lt;/font&gt;&lt;/div&gt;&lt;div style=&quot;&quot;&gt;&lt;font size=&quot;3&quot;&gt;(5V,&amp;nbsp;1 Pin)&lt;/font&gt;&lt;/div&gt;" style="edgeLabel;html=1;align=center;verticalAlign=middle;resizable=0;points=[];" connectable="0" vertex="1" parent="Jj-Pi44mvM_tSbgrSIMR-77">
          <mxGeometry x="-0.0837" y="1" relative="1" as="geometry">
            <mxPoint x="-30" as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-79" value="Text" style="edgeLabel;html=1;align=center;verticalAlign=middle;resizable=0;points=[];fontSize=12;" connectable="0" vertex="1" parent="Jj-Pi44mvM_tSbgrSIMR-77">
          <mxGeometry x="0.803" relative="1" as="geometry">
            <mxPoint as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-80" value="" style="endArrow=classic;html=1;rounded=0;exitX=0.5;exitY=1;exitDx=0;exitDy=0;entryX=0.098;entryY=-0.003;entryDx=0;entryDy=0;entryPerimeter=0;" edge="1" parent="1" source="Jj-Pi44mvM_tSbgrSIMR-1">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="-279.89999999999975" y="-358.65" as="sourcePoint" />
            <mxPoint x="-280.3199999999998" y="-289.9999999999999" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-81" value="12V 3A wall adapter power source&lt;div&gt;&lt;span style=&quot;background-color: rgb(255, 255, 102);&quot;&gt;Qualtek&lt;/span&gt;&lt;br&gt;&lt;div&gt;QFWB-36-12-US01&lt;/div&gt;&lt;/div&gt;" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="40" y="370" width="140" height="90" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-83" value="&lt;p style=&quot;line-height: 120%&quot;&gt;12V 1.5A Voltage Regulator&lt;br&gt;&lt;span style=&quot;background-color: rgb(255, 255, 153);&quot;&gt;Texas Instruments&lt;/span&gt;&lt;/p&gt;&lt;p style=&quot;line-height: 120%&quot;&gt;&lt;span&gt;LM340T-12/NOPB&lt;/span&gt;&lt;/p&gt;" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="50" y="170" width="120" height="70" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-84" value="" style="rounded=0;whiteSpace=wrap;html=1;fillColor=none;dashed=1;" vertex="1" parent="1">
          <mxGeometry x="10" y="110" width="340" height="220" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-85" value="&lt;p style=&quot;line-height: 120%&quot;&gt;5V 1.5A Voltage Regulator&lt;/p&gt;&lt;p style=&quot;line-height: 120%&quot;&gt;Digikey&lt;/p&gt;&lt;p style=&quot;line-height: 120%&quot;&gt;LM317BTG&lt;/p&gt;" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="-340" y="-290" width="120" height="90" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-86" value="" style="rounded=0;whiteSpace=wrap;html=1;fillColor=none;dashed=1;" vertex="1" parent="1">
          <mxGeometry x="-350" y="-300" width="710" height="380" as="geometry" />
        </mxCell>
        <mxCell id="Jj-Pi44mvM_tSbgrSIMR-89" value="" style="endArrow=classic;html=1;rounded=0;exitX=0.5;exitY=0;exitDx=0;exitDy=0;" edge="1" parent="1" source="Jj-Pi44mvM_tSbgrSIMR-81">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="76.67" y="340" as="sourcePoint" />
            <mxPoint x="110.00333333333326" y="240" as="targetPoint" />
          </mxGeometry>
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>



