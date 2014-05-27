# Groupdocs Comparison
============================

GroupDocs Comparison plugin for ezPublish

With GroupDocs Comparison plugin for ezPublish you can easily view on [annotate on PDF's](http://groupdocs.com/apps/annotation), Word documents, Excel documents, Powerpoint documents and more with the GroupDocs Comparison tool, directly from within your ezPublish website.

###Plugin Manual Installation Instructions:
1. "groupdocsComparison" module contain "design, modules, setting", so unzip it into "extentions" directory, so parent directory is "groupdocsComparison"
2. Open file: "site/settings/override/site.ini.append.php" and add "ActiveExtensions[]=groupdocsComparison" under "[ExtensionSettings]"
3. Go to Admin > Setup > Extentions and checkbox where "groupdocsComparison" must be ticked
4. Then go to - Setup > Extentions and press "Regenerate autoloaded arrays for extentions" in the bottom
5. Grant permissions in admin go to - User Accounts > Roles and policies > Anonymous => Edit Role and if "groupdocsComparison" isn't available in the list press - New Policy > choose Module: groupdocsComparison > Grant access to all functions > Save
6. Go to Setup and press "Clear all caches"


###[Sign, Manage, Annotate, Assemble, Compare and Convert Documents with GroupDocs](http://groupdocs.com)
* [Annotate PDF, Word, Excel, Powerpoint and Images with GroupDocs Comparison](http://groupdocs.com/apps/annotation)
* [Download Comparison plugin package here](https://github.com/groupdocs/radiant-groupdocs-annotation)
* [Embed DOC, DOCX, PDF Viewer in your Radiant CMS website] (http://ext.radiantcms.org/extensions/294-groupdocs-viewer)
* [See source code for GroupDocs Comparison plugin for Radiant CMS](https://github.com/groupdocs/radiant-groupdocs-annotation-source)

###Created by [GroupDocs Marketplace Team](http://groupdocs.com/marketplace/plugins).

###ChangeLog
2012-11-30
1.  Client CMS name tracking was added(referer parameter in the URL).
