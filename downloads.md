---
layout: page
title: Downloads
tags: Downloads
icon-class: icon-download
permalink: /downloads/
---

<!-- Table of content -->
<div class="clearfix page_menu">
  <ul class="sections_list">
    <li class="icon-next-page smaller-icon close-icon-2 lrg_blue section_title">
      <span class="lrg_dark bold_font">Sections</span>
    </li>
    <li><a href="#lrg-data">LRG data</a></li>
    <li><a href="#lrg-in-ensembl">LRG in Ensembl</a></li>
    <li><a href="#lrg-xml-schema">XML schema</a></li>
    <li><a href="#lrg-archived-data">Archived data</a></li>
    <li><a href="#web-services">Web services</a></li>
  </ul>  
</div>  


### LRG data

LRG data is available on the [LRG FTP site](ftp://ftp.ebi.ac.uk/pub/databases/lrgex/) in **XML format**.  
The LRG genomic, transcript and protein sequences are also available in **FASTA format** on the [LRG FTP site](ftp://ftp.ebi.ac.uk/pub/databases/lrgex/fasta).

There is the possibility to download all the public and pending LRGs:

<div class="row">
  <div class="col-lg-4 col-lg-offset-4 col-md-4 col-md-offset-4 col-sm-4 col-sm-offset-4 col-xs-4 col-xs-offset-4">
    <table class="table table-hover table-lrg">
      <thead>
        <tr class="sorttable_header">
          <th>Status</th>
          <th colspan="2">Formats (zipped)</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td class="left-col">Public</td>
          <td>
            <a href="ftp://ftp.ebi.ac.uk/pub/databases/lrgex/LRG_public_xml_files.zip">
              <div class="file_link clearfix">
                <div class="left icon-literature close-icon-0"></div>
                <div class="left">XML</div>
              </div>
            </a>
          </td>
          <td>
            <a href="ftp://ftp.ebi.ac.uk/pub/databases/lrgex/fasta/LRG_public_fasta_files.zip">
              <div class="file_link clearfix">
                <div class="left icon-literature close-icon-0"></div>
                <div class="left">FASTA</div>
              </div>
            </a>
          </td>  
        </tr>
        <tr>
          <td class="left-col">Pending</td>
          <td>
            <a href="ftp://ftp.ebi.ac.uk/pub/databases/lrgex/LRG_pending_xml_files.zip">
              <div class="file_link clearfix">
                <div class="left icon-literature close-icon-0"></div>
                <div class="left">XML</div>
              </div>
            </a>
          </td>
          <td>
            <a href="ftp://ftp.ebi.ac.uk/pub/databases/lrgex/fasta/LRG_pending_fasta_files.zip">
              <div class="file_link clearfix">
                <div class="left icon-literature close-icon-0"></div>
                <div class="left">FASTA</div>
              </div>
            </a>
          </td>  
        </tr>
      </tbody>
    </table>
  </div>
</div>

<span class="warning">NOTE:</span> If you can't access to the LRG FTP site through the FTP protocol, you can access it using the HTTP protocol: [LRG FTP site - HTTP](http://ftp.ebi.ac.uk/pub/databases/lrgex/).

<br />  

##### Summary data

<div class="row">
  <div class="col-lg-12 col-md-12 col-sm-12 col-xs-12">
    <table class="table table-hover table-lrg">
      <thead>
        <tr class="sorttable_header">
          <th rowspan="2">Format</th>
          <th rowspan="2">Description</th>
          <th colspan="2" class="split-header">Files location by assembly</th>
        </tr>
        <tr class="sorttable_header">
          <th class="border-left">GRCh37</th>
          <th>GRCh38</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td class="left-col">BED</td>
          <td class="smaller-text">
            The file contains 4 tracks:
            <ul>
              <li>Public LRG genes</li>
              <li>Public LRG transcripts, with their exon(s) coordinates</li>
              <li>Pending LRG genes</li>
              <li>Pending LRG transcripts, with their exon(s) coordinates</li>
            </ul>
          </td>
          <td>
            <a href="ftp://ftp.ebi.ac.uk/pub/databases/lrgex/LRG_GRCh37.bed" target="_blank">
              <div class="file_link clearfix">
                <div class="left icon-literature close-icon-0"></div>
                <div class="left">BED</div>
              </div>
            </a>
          </td>
          <td>
            <a href="ftp://ftp.ebi.ac.uk/pub/databases/lrgex/LRG_GRCh38.bed" target="_blank">
              <div class="file_link clearfix">
                <div class="left icon-literature close-icon-0"></div>
                <div class="left">BED</div>
              </div>
            </a>
          </td>
        </tr>

        <tr>
          <td class="left-col">Tabulated<br /><span class="smaller-text" style="font-weight:normal">(LRG genes)</span></td>
          <td class="smaller-text">
            The file lists the LRG genes in genomic coordinates. The columns are:
            <ul>
              <li>LRG identifier (e.g. LRG_1)</li>
              <li>HGNC symbol (e.g. COL1A1)</li>
              <li>Status (public/pending)</li>
              <li>Chromosome</li>
              <li>Start</li>
              <li>End</li>
              <li>Strand (1 = forward, -1 = reverse)</li>
            </ul>
          </td>
          <td>
            <a href="ftp://ftp.ebi.ac.uk/pub/databases/lrgex/list_LRGs_GRCh37.txt" target="_blank">
              <div class="file_link clearfix">
                <div class="left icon-literature close-icon-0"></div>
                <div class="left">TXT</div>
              </div>
            </a>
          </td>
          <td>
            <a href="ftp://ftp.ebi.ac.uk/pub/databases/lrgex/list_LRGs_GRCh38.txt" target="_blank">
              <div class="file_link clearfix">
                <div class="left icon-literature close-icon-0"></div>
                <div class="left">TXT</div>
              </div>
            </a>
          </td>
        </tr>

        <tr>
          <td class="left-col">Tabulated<br /><span class="smaller-text" style="font-weight:normal">(LRG transcripts, exons, proteins)</span></td>
          <td class="smaller-text">
            The file lists the LRG transcripts, exons and protein in genomic coordinates<br />
            The columns are:
            <ul>
             <li>LRG transcript identifier (e.g. LRG_1t1)</li>
             <li>HGNC symbol (e.g. COL1A1)</li>
             <li >Chromosome</li>
             <li>Strand (1 = forward, -1 = reverse)</li>
             <li>Transcript start</li>
             <li>Transcript end</li>
             <li>List of exons coordinates ("start-end" separated by a comma)</li>
             <li>LRG protein identifier (e.g. LRG_1p1)</li>
             <li>Protein start</li>
             <li>Protein end</li>
            </ul>
          </td>
          <td>
            <a href="ftp://ftp.ebi.ac.uk/pub/databases/lrgex/list_LRGs_transcripts_GRCh37.txt" target="_blank">
              <div class="file_link clearfix">
                <div class="left icon-literature close-icon-0"></div>
                <div class="left">TXT</div>
              </div>
            </a>
          </td>
          <td>
            <a href="ftp://ftp.ebi.ac.uk/pub/databases/lrgex/list_LRGs_transcripts_GRCh38.txt" target="_blank">
              <div class="file_link clearfix">
                <div class="left icon-literature close-icon-0"></div>
                <div class="left">TXT</div>
              </div>
            </a>
          </td>
        </tr>

        <tr>
          <td class="left-col">Tabulated<br /><span class="smaller-text" style="font-weight:normal">(LRG transcripts + external references)</span></td>
          <td class="smaller-text">
            The file lists the LRG transcripts and their external references<br />
            The columns are:
            <ul>
             <li>LRG ID (e.g. LRG_2)</li>
             <li>HGNC symbol (e.g. COL1A2)</li>
             <li>RefSeqGene ID (e.g. NG_007405.1)</li>
             <li>LRG transcript (e.g. t1)</li>
             <li>RefSeq transcript ID with the sequence identical to the LRG transcript (e.g. NM_000089.3)</li>
             <li>Ensembl transcript ID with the sequence identical to LRG transcript (e.g. ENST00000297268.10)</li>
             <li>CCDS ID (e.g. CCDS34682.1)</li>
            </ul>
          </td>
          <td>-</td>
          <td>
            <a href="ftp://ftp.ebi.ac.uk/pub/databases/lrgex/list_LRGs_transcripts_xrefs.txt" target="_blank">
              <div class="file_link clearfix">
                <div class="left icon-literature close-icon-0"></div>
                <div class="left">TXT</div>
              </div>
            </a>
          </td>
        </tr>
      </tbody>
    </table>
  </div>
</div>  


### LRG in Ensembl
  
The list of LRGs already imported in [Ensembl](http://www.ensembl.org){: .icon-external-link} is available in this [text file](ftp://ftp.ebi.ac.uk/pub/databases/lrgex/lrgs_in_ensembl.txt).  
<br />
  
  
### LRG XML schema

The LRG XML schema documentation is downloadable [here](ftp://ftp.ebi.ac.uk/pub/databases/lrgex/docs) and the different versions of the XML schema definitions (RELAX NG format) are available [here](ftp://ftp.ebi.ac.uk/pub/databases/lrgex/docs/schemas).  
The current LRG XML schema version is **{{ site.lrg-schema }}**.  
<br />
  
  
### LRG archived data

Previous versions of the LRGs (in different LRG XML schemas) are available:

<div class="row">
  <div class="col-lg-4 col-lg-offset-4 col-md-4 col-md-offset-4 col-sm-4 col-sm-offset-4 col-xs-4 col-xs-offset-4">
    <table class="table table-hover table-lrg">
      <thead>
        <tr class="sorttable_header">
          <th>Schema version</th>
          <th>Link</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td class="left-col">Schema 1.8</td>
          <td>
            <a class="icon-link smaller-icon close-icon-5" href="ftp://ftp.ebi.ac.uk/pub/databases/lrgex/SCHEMA_1_8_ARCHIVE/" target="_blank">FTP site</a>
          </td>  
        </tr>
        <tr>
          <td class="left-col">Schema 1.7</td>
          <td>
            <a class="icon-link smaller-icon close-icon-5" href="ftp://ftp.ebi.ac.uk/pub/databases/lrgex/SCHEMA_1_7_ARCHIVE/" target="_blank">FTP site</a>
          </td>  
        </tr>
        <tr>
          <td class="left-col">Schema 1.6</td>
          <td>
            <a class="icon-link smaller-icon close-icon-5" href="ftp://ftp.ebi.ac.uk/pub/databases/lrgex/SCHEMA_1_6_ARCHIVE/" target="_blank">FTP site</a>
          </td>  
        </tr>
      </tbody>
    </table>
  </div>
</div>

### Web services

The EMBL-EBI provides [RESTful web services](http://www.ebi.ac.uk/Tools/webservices/services/eb-eye_rest){: .icon-external-link} for LRG.
<div><a class="icon-next-page smaller-icon close-icon-2" href="/web-service">See more</a></div>