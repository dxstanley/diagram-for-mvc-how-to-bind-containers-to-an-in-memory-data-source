# Diagram for MVC - How to bind containers to an in-memory data source

This example demonstrates to bind the Diagram control to an in-memory data source and wrap shapes in horizontal and vertical containers. You need to use the [ContainerKey](https://docs.devexpress.com/AspNet/DevExpress.Web.ASPxDiagram.DiagramNodeMappingInfo.ContainerKey) property to specify the name of a data source field that provides the key of a shape's parent container shape.

<!-- default file list -->
*Files to look at*:

* [Index.cshtml](./CS/DiagramContainers/Views/Home/Index.cshtml) (VB: [Index.vbhtml](./VB/DiagramContainersVB/Views/Home/Index.vbhtml))
* [HomeController.cs](./CS/DiagramContainers/Controllers/HomeController.cs) (VB: [HomeController.vb](./VB/DiagramContainersVB/Controllers/HomeController.vb))
* [Item.cs](./CS/DiagramContainers/Models/Item.cs) (VB: [Item.vb](./VB/DiagramContainersVB/Models/Item.vb))
* [DiagramDataProvider.cs](./CS/DiagramContainers/Models/DiagramDataProvider.cs) (VB: [DiagramDataProvider.vb](./VB/DiagramContainersVB/Models/DiagramDataProvider.vb))
<!-- default file list end -->