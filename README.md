See the [original repo](https://github.com/bblanchon/pdfium-binaries/) for details about this fork.

Our build includes the hooks for the [PDFiumViewer control](https://github.com/pvginkel/PdfiumViewer) as well as targeting `x86`. The resulting `pdfium.dll` can then be copied to our [fork](https://github.com/northwoodspd/PdfiumViewer/tree/master/Libraries) of the viewer control. We have a TeamCity build configuration for that control, which will output a nuget package that can then be consumed by whatever projects need it.
