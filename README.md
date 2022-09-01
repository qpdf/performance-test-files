# QPDF Performance Test Files

These files are used by the [performance_check](https://github.com/qpdf/qpdf/blob/main/performance_check) script in the qpdf source tree.

Here is where the files came from:

* **abuild-manual-1-100.pdf** — the first 100 pages of the manual from [abuild](https://abuild.sourceforge.io/), a retired open source project by the same author as qpdf
* **many-nulls.pdf** — created by [test_many_nulls](https://github.com/qpdf/qpdf/blob/main/qpdf/test_many_nulls.cc) in the qpdf repository
* **pdf-spec-1-100.pdf** — The first 100 pages of the [original ISO PDF spec](https://opensource.adobe.com/dc-acrobat-sdk-docs/standards/pdfstandards/pdf/PDF32000_2008.pdf), decrypted by qpdf
  * The actual file is from an older download but as the same ID as the current download
* pdf-spec-1-100.json — A qpdf JSON file created from **pdf-spec-1-100.pdf**

The [performance_check](https://github.com/qpdf/qpdf/blob/main/performance_check) script looks for a clone of this repository in the same parent directory as extracted qpdf source tree, but the location can be overridden. See the script for details.
