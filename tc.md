# EISENMANN Shanghai

## Teamcenter

Deployment  

1. Storage  
   * Volume  
     * Windows  
     * Linux  
   * Database  
     * Oracle  
     * MS SQL Server  
2. Modeling  
3. Protection  
4. Configuration  
5. Productivity  

***

ZPRD: production / product material

ZKON: construction assembly  

ZHAW: purchased part

ZROH: raw material

ENAP: Eisenmann Auxiliary material

ZLTV  

ZLTA

ZLTS

Z: not SAP standard

T: Teile (Parts)

L: Liste (List)

V: Vorabbeschaffung (Advance procurement / pre order)

A: Auftrag (Order / Project)

S: Service

### Teamcenter 8 -> Penta V8  

## ERP  

### SAP

* ECC ERP Central Component  
* S/4HANA  

```mermaid
graph LR
A[Camos] -->B(SAP)
    B --> D[Teamcenter]
    B --> E[Penta V8]
```

PS: Project Structure  

SD: Sales Distribution  

```mermaid
gantt
dateFormat  YYYY-MM-DD
title Adding GANTT diagram to mermaid
excludes weekdays 2014-01-10

section A section
Completed task            :done,    des1, 2014-01-06,2014-01-08
Active task               :active,  des2, 2014-01-09, 3d
Future task               :         des3, after des2, 5d
Future task2  :         des4, after des3, 5d
```  
