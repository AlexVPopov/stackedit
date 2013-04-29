
Welcome to StackEdit!	{#welcome}
=====================


Hello, I am your first Markdown document within **StackEdit**. Don't delete me, I can be helpful. I can be recovered anyway in the `Utils` tab of the <i class="icon-cog"></i> `Settings` dialog.

----------


Documents
---------

**StackEdit** stores your documents in the browser local storage, which means all your documents are automatically saved locally and are accessible offline.

#### <i class="icon-file"></i> Create a document

You can create a new document by clicking the <i class="icon-file"></i> button in the navigation bar. This will switch from the current document to the new one.

#### <i class="icon-folder-open"></i> Switch to another document

You can list all your local documents and switch from one document to an other by clicking the <i class="icon-folder-open"></i> button in the navigation bar.

#### <i class="icon-pencil"></i> Rename a document

You can rename the current document by clicking the document title in the navigation bar.

#### <i class="icon-trash"></i> Delete a document

You can delete the current document by clicking the <i class="icon-trash"></i> button in the navigation bar.

----------


Synchronization
---------------

**StackEdit** can be combined with **Google Drive** or **Dropbox** to have your documents centralized in the *Cloud*. The synchronization feature will take care of uploading your modifications or download the latest version of your documents.

#### <i class="icon-download"></i> Import a document

You can import a document from the *Cloud* by going to the <i class="icon-gdrive"></i> `Google Drive` or the <i class="icon-dropbox"></i> `Dropbox` sub-menu and by clicking `Import from...`. Once imported, your document will be marked with a <i class="icon-gdrive"></i> or a <i class="icon-dropbox"></i> icon in the navigation bar, which means **StackEdit** will synchronize it with the **Google Drive** / **Dropbox** file.

#### <i class="icon-upload"></i> Export a document

You can export any document by going to the <i class="icon-gdrive"></i> `Google Drive` or the <i class="icon-dropbox"></i> `Dropbox` sub-menu and by clicking `Export to...`. Even if your document is already synchronized with **Google Drive** or **Dropbox**, you can export it to a another location. **StackEdit** can synchronize one document with multiple locations.

#### <i class="icon-refresh"></i> Synchronize a document

Once your document is linked to a **Google Drive** or a **Dropbox** file, **StackEdit** will periodically (every 3 minutes) synchronize it by downloading/uploading any modifications. Any conflict will be detected, and a local copy of your document will be created as a backup if necessary. If you have just modified your document and you want to force the synchronization, click the <i class="icon-refresh"></i> button in the navigation bar.

> **NOTE:** The <i class="icon-refresh"></i> button is disabled when:
> 
> - you are offline,
> - or the document is not synchronized with any location,
> - or the document has not been modified since the last synchronization.

#### <i class="icon-refresh"></i> Manage document synchronization

Since one document can be synchronized with multiple locations, you can list and manage synchronized locations by clicking <i class="icon-refresh"></i> `Manage synchronization` in the <i class="icon-stackedit"></i> menu. This will open a dialog box where you will be able to add or remove synchronization links that are associated to your document.

> **NOTE:** If you delete the file on **Google Drive** or on **Dropbox**, the document will no longer be synchronized with that location.

----------


Publication
-----------

Once you are happy with your document, you can publish it on different websites directly from **StackEdit**.

#### <i class="icon-share"></i> Publish a document

You can publish your document by going to the <i class="icon-share"></i> `Publish on` sub-menu and by choosing a website. In the dialog box, you can choose the publication format:

- Markdown, to publish the Markdown text on a website that can interpret it (**GitHub** for instance),
- HTML, to publish the document converted into HTML (on a blog for instance),
- Template, to have a full control of the output.

> **NOTE:** The default template is a simple webpage which wraps your document in HTML format. You can customize it in the `Publish` tab of the <i class="icon-cog"></i> `Settings` dialog.

#### <i class="icon-share"></i> Update a publication

After publishing, **StackEdit** will keep your document linked to that publish location so that you can update it easily. Once you have modified your document and you want to update your publication, click on the <i class="icon-share"></i> button in the navigation bar.

> **NOTE:** The <i class="icon-share"></i> button is disabled when:
> 
> - you are offline,
> - or the document has not been published anywhere.

#### <i class="icon-share"></i> Manage document publishing

Since one document can be published on multiple locations, you can list and manage publish locations by clicking <i class="icon-share"></i> `Manage publishing` in the <i class="icon-stackedit"></i> menu. This will open a dialog box where you will be able to add or remove publication links that are associated to your document.

> **NOTE:** In some cases, if you remove the file from the website or the post from the blog, the document will no longer be published on that location.

----------


Markdown Extra
--------------

**StackEdit** supports **Markdown Extra**, which extends **Markdown** syntax with some nice features.


### Tables

**Markdown Extra** has a special syntax for tables:

Item      | Value
--------- | -----
Computer  | $1600
Phone     | $12
Pipe      | $1

You can specify column alignment with one or two colons:

| Item      | Value | Qty  |
| :-------- | -----:| :--: |
| Computer  | $1600 |  5   |
| Phone     |   $12 |  12  |
| Pipe      |    $1 | 234  |


### Definition Lists

**Markdown Extra** has a special syntax for definition lists too:

Term 1
Term 2
:   Definition A
:   Definition B

Term 3

:   Definition C

:   Definition D

	> part of definition D


### Fenced code blocks

**GitHub**'s fenced code blocks are also supported with **Prettify** syntax highlighting:

```
// Foo
var bar = 0;
```


### Special Attributes

With **Markdown Extra**, you can specify `class` and `id` attributes on headers and fenced code blocks just like this:

##### Title example {#my-title}

``` {#my-id .my-class}
var foo = bar;
```

Then you can create cross-references like this: [beginning of the document](#welcome).


> **NOTE:** You can find more information about **Markdown** syntax [here][1] or about **Markdown Extra** [here][2].

----------


  [1]: http://daringfireball.net/projects/markdown/syntax "Markdown"
  [2]: http://michelf.ca/projects/php-markdown/extra/ "Markdown Extra"