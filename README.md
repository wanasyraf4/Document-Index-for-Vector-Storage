# Document-Index-for-Vector-Storage

## Form 1
```
{
  "chunk_id": "guideline_001_p1",
  "page": 1,
  "section": "1.0 Introduction",
  "text": "The internal audit function in the Labuan banking industry is of paramount importance...",
  "metadata": {
    "section_type": "body",
    "image_refs": []
  }
}
```

image ref can be

```
"image_refs": [
  {
    "image_id": "img_guideline_p5_fig3",
    "caption": "Figure 3 – Internal Audit Process Flow Diagram",
    "file_path": "<path>",
    "file_url": "https://nautilus.labuanfsa.local/storage/guidelines/audit_flow_p5.png",
    "page_region": "center"
  }
]
```


### Sample Integration

```
[
  {
    "document_title": "GUIDELINES ON MINIMUM AUDIT STANDARDS FOR INTERNAL AUDITORS OF LABUAN BANKS",
    "document_metadata": {
      "issuer": "Labuan Financial Services Authority (Labuan FSA)",
      "category": "Banking Guidelines",
      "issued_date": "2014-06-06",
      "clarification_note_date": "2025-06-30",
      "language": "English",
      "source_url": "https://www.labuanfsa.gov.my/clients/asset_120A5FB8-61B6-45E8-93F0-3F79F86455C8/contentms/img/documents/Legislation_and_Guidelines/Guidelines/banking/2025/CN-on-GLs-on-Minimum-Audit-Stds-for-Internal-Auditors-of-Lbn-Banks_30062025.pdf"
    },
    "chunks": [
      {
        "chunk_id": "guideline_001_p1",
        "page": 1,
        "section": "1.0 Introduction",
        "text": "The internal audit function in the Labuan banking industry is of paramount importance in the context of the change and growth in this industry. Increased competition, pressure to operate profitably or to improve performance, introduction of new financial products and the change in information technologies could result in management giving inadequate emphasis to sound operational and risk controls.",
        "metadata": {
          "section_type": "body",
          "image_refs": []
        }
      },
      {
        "chunk_id": "guideline_001_p2",
        "page": 2,
        "section": "1.1 Objective",
        "text": "It is therefore incumbent upon management to enhance and to upgrade the internal audit function so as to enable internal auditors to play a more proactive and meaningful role in assisting Labuan banks to achieve sound and stable growth. The purpose of this guideline is to outline minimum standards expected of the internal audit function, ensuring consistency and sound governance across all Labuan banks.",
        "metadata": {
          "section_type": "body",
          "image_refs": [
            {
              "image_id": "img_guideline_p2_fig1",
              "caption": "Figure 1 – Overview of Internal Audit Governance Structure",
              "file_url": "https://nautilus.labuanfsa.local/storage/guidelines/2025/internal_audit_fig1.png",
              "page_region": "bottom"
            }
          ]
        }
      }
    ]
  },
  {
    "document_title": "ADMISSIBILITY FRAMEWORK FOR DIGITAL CURRENCIES",
    "document_metadata": {
      "issuer": "Labuan Financial Services Authority (Labuan FSA)",
      "category": "Digital Finance Guidelines",
      "issued_date": "2025-03-01",
      "clarification_note_date": null,
      "language": "English",
      "source_url": "https://www.labuanfsa.gov.my/clients/asset_120A5FB8-61B6-45E8-93F0-3F79F86455C8/contentms/img/documents/Legislation_and_Guidelines/Guidelines/digital/2025/Admissibility_Framework_for_Digital_Currencies_01032025.pdf"
    },
    "chunks": [
      {
        "chunk_id": "guideline_002_p1",
        "page": 1,
        "section": "1.0 Introduction",
        "text": "This framework sets out the principles and criteria for the admissibility of digital currencies and stablecoins within the Labuan International Business and Financial Centre (IBFC). It provides guidance to financial institutions on the assessment of digital assets for financial operations and reporting under Labuan FSA’s prudential supervision.",
        "metadata": {
          "section_type": "body",
          "image_refs": []
        }
      },
      {
        "chunk_id": "guideline_002_p2",
        "page": 2,
        "section": "2.0 Scope of Application",
        "text": "This framework applies to all Labuan licensed entities engaged in activities involving digital currencies, including exchanges, custodians, and financial intermediaries. Entities are required to perform due diligence and ensure compliance with anti-money laundering (AML) and counter-financing of terrorism (CFT) requirements prior to the acceptance of any digital asset.",
        "metadata": {
          "section_type": "body",
          "image_refs": [
            {
              "image_id": "img_guideline_002_p2_table1",
              "caption": "Table 1 – Digital Asset Classification and Risk Weighting",
              "file_url": "https://nautilus.labuanfsa.local/storage/guidelines/2025/digital_currency_table1.png",
              "page_region": "center"
            }
          ]
        }
      }
    ]
  }
]
```


## Form 2
```
[
  {
    "text":"Title \n\n1.0 ParaA \n\nBody of text \n\n Page 1 of 4 \n\n\f 1.2 ParaB \n\nBody of text",
    "source":"http ...."
  }
]
```
