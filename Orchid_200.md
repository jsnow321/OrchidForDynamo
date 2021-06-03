**Versioning:** Number syntax: Major.Minor.Build.Revision (x.x.x.x).  
The major number follows the Dynamo version, 200.x.x is usable in Dynamo +2.0.x.x versions. The minor number is internal major builds. The build number is internal minor builds. The revision number is an internal build number without public documentation and display in this file.  
  
### History of Orchid for Dynamo 2.0.x  
  
200.4.0  
- Nodes for (MEP) System is extended with many functions.  
- Nodes for Reference and Assembly is added.  
- A wide range of Geometry functions (Nodes) is added.  
  
200.3.0  
- Version number changed from 204 to 200 to support two-digit Dynamo minor versioning. By this the Dynamo build number has been deprecated in the version number. Before 204 = 2.0.4, now 200 = 2.0.x.  

204.2.0  
- Support for external applications is moved to independent assemblies, this includes support for IfxExport.
  
204.1.4  
- Filters, Schedules, and parameter Definitions (project and family parameters) added.  
  
203.1.3  
- Refactoring of Core nodes, nodes are moved into Common. Several other functions are also refactored into other namespaces.  
  
203.1.2  
- Rebuild of classes so types not provided by the dynamo team now are wrapped into Orchid types.  
  
203.1.1	 
- Element: nodes for views, and view templates.  
  
203.1.0  
- Element: nodes for spatial elements, grouping, views, viewports, and grids.  
  
202.5.0  
- Total refactored and major parts recoded.  

202.4.2  
- Core: nodes for BuiltInParameter. Nodes for copying and transferring elements between different documents. Nodes for opening, save and closing central files. Nodes for linking files into documents.  

202.4.1  
- Materials: +100 new nodes for materials in a new branch.  

202.4.0  
- Element: Selection.ElementByFamily and Families.  
- Core: IFC export – IFC.SettingGeneral, IFC.SettingAdditional, IFC.SettingProperty, IFC.SettingAdvanced, IFC.Export, IFC File Type, IFC Setting, IFC Version, IFC Level Of Detail, IFC Site Placement, and IFC Space Boundary.  
- Core: String.Substring, String.Replace, Document.OpenView, Project.SetProjectLocation, Project.GetProjectLocation, Project Origin, and Phases.  

202.3.11  
- Nodes for associate - Elements: Parameter.Associate, Parameter.HasAssociated, Parameter.GetAssociated, Family.HasAssociated, FamilyType.HasAssociated, FamillyDocument: Parameter.HasAssociated, Nested.GetAssociated.  
- Element: Category.BuiltInCategory, Category.InDocument, Category.CategoryType, Category.ByCategoryType, Element.Settype.  
- Core: Math.Random, Math.RandomList.  

202.3.10  
- Package refactored to comply with naming conventions  
- Primary support for Dynamo version changed to 2.0.2.x  
- Parameter: ProjectParameters, SharedParameters, GlobalParameters, AddIfcParameters (in document and Family document)  
- FamilyName (for element and element type), ElementType.Name  
- FamillyDocument: Convert (from shared to normal parameter)  

201.3.9  
- SharedParameter: SetFile, GroupByGroupName, GroupByType.  

201.3.8  
- Installer split into two parallels, 132.x.x.x and 201.x.x.x version installer.  
- Family All and ByCategory / FamilyType All and ByCategory.  
- Nodes for Subcategory, create, remove, get by category and by name.  

201.3.7  
- Last Custom Nodes turned into ZeroTouch nodes --> nodes for FEM-design.  
- Nodes for Materials created and nodes for Document.contain (Category/Types)  
- Purge nodes updated, comes in a PostCommand and a Document version.  

201.3.6  
- Print: Nodes to handle printing, several nodes created.  

201.3.5  
- SystemFamily: CreateCompoundLayer, DeleteCompoundLayer, SetCompoundLayerWidth, and two dropdown nodes added.  

201.3.4  
- Core: Directory.Current, Directory.FromPath and File.FromPath nodes added.  

201.3.3  
- FamilyDocument: GetCategory and SetCategory node for the document added. Tooltip added AddParameter, AddsharedParameter.  

201.3.2  
- Application: All Sigma nodes are updated supporting live connection.  

201.3.1  
- FamilyDocument: Parameters.GetValue and Parameters.SetValue updated.  

201.3.0  
- Support for Dynamo version changed to 2.0.1.x  

200.3.0  
- FamilyDocument class split into subclasses. New names for all nodes in the FamilyDocument class.  

200.2.7  
- FamilyDocument.Parameters node added.   

200.2.6  
- Parameter nodes added: AddProjectParameter, AddSharedParameter, ChangeCategory, and DeleteParameter.  

200.2.5  
- Element nodes updated to take list of documents.  

200.2.4  
- FamilyDocument.AddParameter node added for Category input (FamilyType).  

200.2.3  
- 6 new nodes added: Object.ToAutodeskElement, Object.ToDynamoElement, FamilyDocument.AddLookupTable, FamilyDocument.AssociateParameter, FamilyDocument.GetNestedFamily, and FamilyDocument.GetNestedFamilyType.  

200.2.2  
- Node icons updated.  

200.2.1  
- Document.ImportImage node added.  

200.2.0  
- Orchid package updated supporting Dynamo Sandbox/Studio.  
- Document.Save and Document.SaveAs nodes added.  

200.1.3  
- FamilyDocument.RenameParameter node added.  

200.1.2  
- Family.GetFamilyDocument node added.  

200.1.1  
- FamilyDocument.IsReportingParameter node is added.  

200.1.0  
- 1st version of Orchid only available at Github.  

200.0.0  
- 1st version of Orchid, primarily upgraded from the DanEDU package.  
