# The Starting Point for Next-Generation Threat Intelligence Analysis Focusing on CTI Data Sources and Datasets

## Universal Framework for Constructing Threat Intelligence Analysis Datasets
<div>
</div>

## CTI Sharing Standards/Frameworks
<table style="display: grid; place-items: center; width: 100%; overflow: auto;">
<caption style="text-align: center;">Table 1 Common Threat Intelligence Sharing Standards/Frameworks Description</caption>
    <tr>
        <th>Standard</th>
        <th>Description</th>
        <th>Built Time</th>
    </tr>
    <tr>
        <td>MAEC</td>
        <td>Standardized language for describing structured information about malware</td>
        <td>2011</td>
    </tr>
    <tr>
        <td>CAPEC</td>
        <td>Standardized language for describing common attack pattern</td>
        <td>2007</td>
    </tr>
    <tr>
        <td>CybOX</td>
        <td>Standardized language for describing cyber events,etc.</td>
        <td>2011</td>
    </tr>
    <tr>
        <td>TAXII</td>
        <td>Application layer protocol for exchanging CTI based on HTTPS</td>
        <td>2013</td>
    </tr>
    <tr>
        <td>STIX</td>
        <td>Standardized language for describing cybersecurity threat information</td>
        <td>2012</td>
    </tr>
    <tr>
        <td>ATT&CK</td>
        <td>Standardized framework and knowledge base, including detailed TTPs</td>
        <td>2013</td>
    </tr>
</table>

## CTI Data Sources

<table style="display: grid; place-items: center;width: 100%; overflow: auto;">
    <caption style="text-align: center;">Table 2 Classification of Indirect Threat Intelligence Data Sources</caption>
    <tr>
        <th>Data Type</th>
        <th>Intelligence Type</th>
        <th>Enterprise</th>
    </tr>
    <tr>
        <td rowspan="6">Structural</td>
        <td rowspan="3">Vulnerabilities and Defects</td>
          <td>
          <a href="https://nvd.nist.gov/">NVD</a><sup>a</sup><br>
          </td>
    </tr>
    <tr>
        <td>
        <a href="https://cve.mitre.org/">CVE</a><sup>b</sup><br>
        </td>
    </tr>
    <tr>
        <td>
        <a href="https://cwe.mitre.org/">Mitre CWE</a><sup>b</sup><br>
        </td>
    </tr>
    <tr>
        <td rowspan="3">IoC Database</td>
        <td>
        <a href="https://whois.whoisxmlapi.com/">Whois</a><sup>c</sup><br>
        </td>
    </tr>
     <tr>
        <td>
        <a href="https://www.farsightsecurity.com/">DNSDB</a><sup>c</sup><br>
        </td>
    </tr>
    <tr>
        <td>
        <a href="https://www.ip2location.com/">IP2Location5</a><sup>c</sup><br>
        </td>
    </tr>
    <tr>
        <td rowspan="3">Semi- structured</td>
        <td rowspan="2">Threat Indicators and Descriptions</td>
        <td>
        <a href="https://otx.alienvault.com/">AlienVault OTX</a><sup>c</sup><br>
        </td>
      <tr>
        <td>
        <a href="https://exchange.xforce.ibmcloud.com/">IBM X-Force</a><sup>c</sup><br>
        </td>
    </tr>
    <tr>
        <td >TTPs Knowledge Base</td>
        <td>
        <a href="https://attack.mitre.org/">Mitre ATT&CK</a><sup>b</sup><br>
        </td>
    </tr>
    </tr>
    <tr>
        <td rowspan="11">Unstructured</td>
        <td rowspan="5">Comprehensive intelligence</td>
        <td>
        <a href="https://www.cisa.gov/">CISA(US)</a><sup>a</sup><br>
        </td>
        <tr>
        <td>
        <a href="https://www.cnnvd.org.cn/home/warn">CNNVD(CN)</a><sup>a</sup><br>
        </td>
    </tr>
    <tr>
        <td>
        <a href="https://www.jpcert.or.jp/">JPCERT/CC(JPN)</a><sup>a</sup><br>
        </td>
    </tr>
    <tr>
        <td>
        <a href="https://www.cirt.gov.bd/">BGD e-GOV CIRT(BD)</a><sup>a</sup><br>
        </td>
    </tr>
    <tr>
        <td>
        <a href="https://www.cyber.gov.au/">ACSC(AU)</a><sup>a</sup><br>
        </td>
    </tr>
    <tr>
        <td rowspan="6">Threat Reports, Alerts, and Blogs</td>
        <td >
        <a href="https://press.kaspersky.com/">Kaspersky</a><sup>c</sup><br>
        </td>
    </tr>    
    <tr>
        <td >
        <a href="https://www.fireeye.com/">FireEye</a><sup>c</sup><br>
        </td>
    </tr>
    <tr>
        <td >
        <a href="https://symantec-enterprise-blogs.security.com/">Symantec</a><sup>c</sup><br>
        </td>
    </tr>
    <tr>
        <td >
        <a href="https://ti.qianxin.com/vulnerability/list">Qianxin</a><sup>c</sup><br>
        </td>
    </tr>
    <tr>
        <td >
        <a href="https://x.threatbook.com/v5/vulIntelligence">ThreatBook</a><sup>c</sup><br>
        </td>
    </tr>
    <tr>    
        <td >
        <a href="https://developer.x.com/">Twitter</a><sup>c</sup><br>
        </td>
    </tr>
</table>
<caption >a:National Agencies b:Non-profit Organization  c:(Security) Supplier</caption>    
    
    


## CTI Analysis Datasets Classification System
<table style="display: grid; place-items: center;width: 100%; overflow: auto;">
    <caption style="text-align: center;">Table 3 A Classification Framework for CTI Analysis Datasets</caption>
    <tr>
      <th style="text-align: center;">Research Field</th>
      <th style="text-align: center;">Sources Data Type</th>
      <th style="text-align: center;" colspan="2">Research Sub-field</th>
      <th style="text-align: center;">Public Dataset</th>
      <th style="text-align: center;">Private Dataset</th>
    </tr>
    <tr style="text-align: center;">
      <td rowspan="3">CTI Knowledge Graph Construction</td>
      <td rowspan="3">Unstructured</td>
      <td rowspan="2">Pipeline Extraction</td>
      <td rowspan="1">Entity Relation</td>
      <!-- <td>6</td> -->
      <td>
      <a href="https://github.com/SCreaMxp/DNRTI-A-Large-scale-Dataset-for-Named-Entity-Recognition-in-Threat-Intelligence">DNRTI(2020-8)</a><br>
      <!-- [Q2012] -->
      <a href="https://github.com/wangxuren/APTNER">APTNER(2021-9)</a><br>
      <!-- [QB003] 中-->
      <a href="https://github.com/aiforsec/CyNER">CyNER(2022-2)</a><br>
      <!-- [QB004] -->
      <a href="https://github.com/luoluoluoyl/relation_extract_dataset">TINRE(2020-12)</a><br>
      <!-- [QB008] -->
      <a href="https://github.com/MuYu-z/CDTier">CDTier(2022-10)</a><br>
      <!-- [Q2001] -->
      <a href="https://github.com/Mhackiori/STIXnet">STIXnet(2023-3)</a><br>
      <!-- [C2004] -->
      </td>
      <td>
      <b>[34]</b>
      <b>[57]</b>
      <b>[95]</b>
      </td>
    </tr>
    <tr style="text-align: center;">
      <td>Construction of KG</td>
      <td >
      <a href="https://github.com/aiforsec/MALOnt">MALOnt(2020-10)</a><br>
      <!-- [QB022] -->
      <a href="https://github.com/stucco-archive/ontology">Stucco(2013-6)</a><br>
      <!-- [QB020] -->
      <a href="https://github.com/IS5882/Open-CyKG">Open-CyKG(2021-6)</a><br>
      <!-- [QB018] -->
      </td>
      <td>
      <b>[60]</b>
      <b>[59]</b>
      <b>[62]</b>
      <b>[1]</b>
      <b>[61]</b>
      <b>[65]</b>
      </td>
    <tr style="text-align: center;">
      <td colspan="2">Joint Extraction</td>
      <td >
      <a href="https://github.com/wangxtz/CVTIKG">CVTIKG(2024-3)</a><br>
      <!-- [QB005] -->
      <a href="https://www.kaggle.com/datasets/Cornell-University/arxiv">HSNMFk-SPLIT:arXiv Dataset</a><br>
      <!-- [QB021] -->
      </td>
      <td>
      <b>[66]</b>
      <b>[68]</b>
      </td>
    </tr>
    <tr style="text-align: center;">
      <td rowspan="4">TTP Identification and Analysis</td>
      <td rowspan="2">Semi-structured</td>
      <td colspan="2">TTPs Mapping</td>
      <td >
      <a href="https://github.com/dessertlab/cti-to-mitre-with-nlp/tree/main">CTI-to-MITRE(2022-5)</a><br>
      <!-- [C1007] -->
      <a href="https://github.com/MuscleFish/RENet">RENet(2021-9)</a><br>
      <!-- [QB001] 中-->
      <a href="https://github.com/MuscleFish/SeqMask">SeqMask(2021-9)</a><br>
      <!-- [Q1008] 中-->
      <a href="https://github.com/MuscleFish/SATG">SATG(2023-3)</a><br>
      <!-- [C1012] -->
      </td>
      <td>
      <b>[30]</b>
      </td>
    </tr>
    <tr style="text-align: center;">
      <td colspan="2">TTPs Association</td>
      <td >-</td>
      <td>
      <b>[76]</b>
      </td>
    </tr>
    <tr style="text-align: center;">
      <td rowspan="2">Unstructured</td>
      <td colspan="2">TTPs Mapping</td>
      <td >
      <a href="https://github.com/KaiLiu-Leo/TTPDrill-0.5?tab=readme-ov-file">TTPDrill(2020-5)</a><br>
      <!-- [Q2005] -->
      <a href="https://github.com/vlegoy/rcATT">rcATT(2019-9)</a><br>
      <!-- [QB024] -->
      </td>
      <td>
      <b>[77]</b>
      <b>[48]</b>
      </td>
    </tr>
    <tr style="text-align: center;">
      <td colspan="2">Unstructured</td>
      <td >-</td>
      <td>
      <b>[79]</b>
      </td>
    </tr>
    <tr style="text-align: center;">
      <td rowspan="2">Event and Relationship Extraction</td>
      <td>Unstructured</td>
      <td colspan="2">Event Extraction</td>
      <td >
      <a href="https://github.com/tangyunzi/TCEDCL">TCEDCL(2023-5)</a>
      </td>
      <td>
      <b>[49]</b>
      </td>
    </tr>
    <tr style="text-align: center;">
      <td>Structural</td>
      <td colspan="2">Event Relationship Extraction</td>
      <td >-</td>
      <td>
      <b>[3]</b>
      </td>
    </tr>
    <tr style="text-align: center;">
      <td>Cross-Direction Integration analysis</td>
      <td rowspan="2">Unstructured</td>
      <td colspan="2">KG and IoC, IoC and TTPs, TTPs and KG, IoC and Events</td>
      <td >
      <a href="https://github.com/li-zhenyuan/Knowledge-enhanced-Attack-Graph">AttacKG(2023-5)</a><br>
      <!-- [QB019] -->
      <a href="https://github.com/TCENet/TCENet-TTP-Data">TCENet(2021-10)</a><br>
      <!-- [Q2010] -->
      <a href="https://github.com/lingren0/TriCTI">TriCTI(2021-1)</a><br>
      <!-- [Q2013] -->
      </td>
      <td>
      <b>[81]</b>
      </td>
    </tr>
    <tr style="text-align: center;">
      <td>Social media data analysis</td>
      <td colspan="2">Immediate streaming data, Non-immediate data</td>
      <td >
      <a href="https://github.com/behzadanksu/cybertweets">CyberTweets (2018-10)</a><br>
      <!-- [QB006] -->
      <a href="https://github.com/ndionysus/twitter-cyberthreat-detection">VulTweets(2019-3)</a><br>
      <!-- [C2010] -->
      <a href="https://github.com/TIPrompt/TI-Prompt">TI-Prompt(2022-1)</a><br>
      <!-- [C2013] -->
      <a href="https://github.com/DrSufi/CyberThreatIndex">CyberThreatIndex(2022-12)</a><br>
      <!-- [Q2011] -->
      </td>
      <td>
      <b>[87]</b>
      </td>
    </tr>
</table>
<caption >The reference numbers in the Private Dataset correspond to the reference numbers of the cited literature in the article.
</caption>
