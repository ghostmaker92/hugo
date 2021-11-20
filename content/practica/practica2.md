+++
chapter = true
pre = "<b>1.2. </b>"
title = "Practica 2"
weight = 4
draft = false
+++
# USO DE MERMAID
{{< mermaid align="left" >}}
graph LR;
A[Jefe] -->|Manda| B(Empleados)
B --> C{<strong>Hacer_Caso</strong>}
C -->|Sí| D[Resultados OK!]
C -->|No| E[Resultados Castastróficos]
{{< /mermaid >}}

# USO DE WARNING
{{% notice warning %}}
Important!! 
{{% notice %}}
