**Versioning:** Number syntax: Major.Minor.Build.Revision (x.x.x.x).  
The major number follows the Dynamo version, 130.x.x is usable in Dynamo +1.3.0.x versions. The minor number is internal major builds. The build number is internal minor builds. The revision number is an internal build number without public documentation and display in this file.  


### History of Orchid for Dynamo 1.3.x ###  
  
134.7.0  
- Support for external applications are moved to independent assemblies, this includes support for IfxExport.
  
134.6.4  
- Filters, Schedules and parameter Definitions (project and family parameters) added.  
  
134.6.3  
- Refactoring of Core nodes, nodes are moved into Common. Several other functions are also refactored into other namespaces.  
  
134.6.2  
- Rebuild of classes so types not provided by the dynamo team now wrapped into Orchid types.  
  
134.6.1	 
- Element: nodes for views, and viewtemplates.  
  
134.6.0  
- Element: nodes for spatial elements, grouping, views, viewports, and grids.  
  
134.5.0  
- Total refactored and major parts recoded.  
  
134.4.2  
- Core: nodes for BuiltInParameter. Nodes for copying and transferring elements between different document. Nodes for opening, save and closing central files. Nodes for linking files into documents.
  
134.4.1  
- Materials: +100 new nodes for materials in a new branch.  
  
134.4.0  
- Element: Selection.ElementByFamily and Families.  
- Core: IFC export – IFC.SettingGeneral, IFC.SettingAdditional, IFC.SettingProperty, IFC.SettingAdvanced, IFC.Export, IFC File Type, IFC Setting, IFC Version, IFC Level Of Detail, IFC Site Placement, and IFC Space Boundary.  
- Core: String.Substring, String.Replace, Document.OpenView, Project.SetProjectLocation, Project.GetProjectLocation, Project Origin, and Phases.  
  
134.3.11  
- Nodes for associate - Elements: Parameter.Associate, Parameter.HasAssociated, Parameter.GetAssociated, Family.HasAssociated, FamilyType.HasAssociated, FamillyDocument: Parameter.HasAssociated, Nested.GetAssociated.  
- Element: Category.BuiltInCategory, Category.InDocument, Category.CategoryType, Category.ByCategoryType, Element.Settype.  
- Core: Math.Random, Math.RandomList.  
  
134.3.10  
- Package refactored to comply with naming convensions  
- Primary support for Dynamo version changed to 1.3.4.x  
- Parameter: ProjectParameters, SharedParameters, GlobalParameters, AddIfcParameters (in document and Family document)  
- FamilyName (for element and element type), ElementType.Name  
- FamillyDocument: Convert (from shared to normal parameter)  
  
132.3.9  
- SharedParameter: SetFile, GroupByGroupName, GroupByType.  
  
132.3.8  
- Installer split into two parallels, 132.x.x.x and 201.x.x.x version installer.  
- Family All and ByCategory / FamilyType All and ByCategory.  
- Nodes for Subcategory, create, remove, get by category and by name.  
  
132.3.7  
- Last Custom Nodes turned into ZeroTouch nodes --> nodes for FEM-design.  
- Nodes for Materials created and nodes for Document.contain (Category/Types)  
- Purge nodes updated, comes in a PostCommand and a Document version.  
  
132.3.6  
- Print: Nodes to handle printing, several nodes created.  
  
132.3.5  
- SystemFamily: CreateCompoundLayer, DeleteCompoundLayer, SetCompoundLayerWidth, and two dropdown nodes added.  
  
132.3.4  
- Core: Directory.Current, Directory.FromPath and File.FromPath nodes added.  
  
132.3.3  
- FamilyDocument: GetCategory and SetCategory node for the document added. Tooltip added AddParameter, AddsharedParameter.  
  
132.3.2  
- Application: All Sigma nodes is updated supporting live connection.  
  
132.3.1  
- FamilyDocument: Parameters.GetValue and Parameters.SetValue updated.  
  
132.3.0  
- Support for Dynamo version changed to 1.3.2.x  
  
130.3.0  
- FamilyDocument class split into subclasses. New names for all nodes in the FamilyDocument class.  
  
130.2.7  
- FamilyDocument.Parameters node added.   
  
130.2.6  
- Parameter nodes added: AddProjectParameter, AddSharedParameter, ChangeCategory, and DeleteParameter.  
  
130.2.5  
- Element nodes updated to take list of document.  
  
130.2.4  
- FamilyDocument.AddParameter node added for Category input (FamilyType).  
  
130.2.3  
- 6 new nodes added: Object.ToAutodeskElement, Object.ToDynamoElement, FamilyDocument.AddLookupTable, FamilyDocument.AssociateParameter, FamilyDocument.GetNestedFamily, and FamilyDocument.GetNestedFamilyType.  
  
130.2.2  
- Node icons updated.  
  
130.2.1  
- Document.ImportImage node added.  
  
130.2.0  
- Orchid package updated supporting Dynamo Sandbox/Studio.  
- Document.Save and Document.SaveAs nodes added.  
  
130.1.3  
- FamilyDocument.RenameParameter node added.  
  
130.1.2  
- Family.GetFamilyDocument node added.  
  
130.1.1  
- FamilyDocument.IsReportingParameter node is added.  
  
130.1.0  
- 1st version of Orchid only available at Github.  
  
130.0.0  
- 1st version of Orchid, primarily upgraded from the DanEDU package.  
  