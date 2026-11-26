# Feria Sostenible | Exhibitor Research and Marketing Analytics

## Project Overview

During my advertising and marketing internship at Onegona, I researched prospective exhibitors and strategic partners for Feria SOStenible and organized the records in Excel. This case shows how the research could inform outreach priorities and includes a separate, simulated example of how the fair could measure interest in exhibition stands.

## Business Context

Feria SOStenible brought sustainable products and responsible consumption initiatives to a public audience in Panama City. The commercial challenge was to identify relevant organizations for the fair and give the team a way to decide which prospects to review first. [Ciudad del Saber event listing](https://ciudaddelsaber.org/eventos/feria-sostenible)

## My Contribution at Onegona

I manually reviewed sustainability-related profiles, recorded prospect information in Excel, and grouped prospects by area of activity for outreach planning. The workbook records each prospect’s sustainability category and a relevance field. The category analysis below uses the category field. The preserved files do not establish a consistent scoring rule for the relevance field.

The campaign materials also describe plans for positioning the fair through content, digital promotion, and audience engagement. Those plans provide context for the research. The findings below come from the prospect workbook.

## Analytical Workflow

| Source | Scope | Use in this case |
| --- | --- | --- |
| General prospect workbook, version dated February 24, 2025 | 99 prospect records in `Sheet1 verificados` | Earlier version used to check which records carried forward. |
| Prospect workbook, version dated February 27, 2025 | 114 prospect records in `Sheet1 verificados`, rows 2–115 | Source for the chart. The 18 rows in `Sheet2 sin verificar` are outside this count. |

For this case study, each populated row in the verified worksheet counts as one prospect. Duplicate checks used normalized names and Instagram profile fields. Matching the two versions on the normalized profile field showed that all 99 earlier records carried forward and 15 records were added. Each record contributes to one category. Case, spelling, and accent variants were combined. Clean energy and renewable energy remain separate because the workbook labels them separately.

Here, **verified** refers to the workbook tab used for the analysis. The chart describes research coverage. Participation and outreach outcomes would require separate records.

## Key Findings

<img src="images/01-researched-prospects-by-category.png" alt="Horizontal bar chart of 114 researched prospects. Recycling through transformation 24, biodegradable products 22, circular economy 20, sustainability services 17, recycling by volume 14, renewable energy 14, clean energy 2, and electric mobility 1." width="800">

Recycling through transformation, biodegradable products, and circular economy accounted for **66 of 114 records**. The team could use those categories as starting points for reviewing outreach prospects. If the fair wanted broader coverage, clean energy and electric mobility were categories where the team could research more organizations. The counts describe the workbook’s research coverage. Assessing market size or demand would require a different source.

## Portfolio Extension | Measuring Exhibitor Interest

**Business question** — Among sessions that reach the Products page, what share reach the stand options and then click the lower WhatsApp button?

### Proposed Measurement Plan

The public Products page lists stand options and offers a lower **Escríbenos** button as well as a separate WhatsApp shortcut near the top. The proposed sequence follows the path through the stand options to the lower button. [Feria SOStenible Products page](https://feriasostenible.com/productos/)

| Step | Proposed event | When to record it |
| --- | --- | --- |
| Open the Products page | `products_view` | The Products page loads. |
| Reach the stand options | `stand_options_view` | The stand-options section becomes visible. |
| Click the lower WhatsApp button | `exhibitor_whatsapp_click` | The visitor clicks the lower **Escríbenos** button. |

In a possible GA4 implementation, count each step once per session and require the steps to occur in order. Validate the visibility and click events on mobile and desktop, and distinguish the lower button from the top shortcut. The final event would measure a click. Messages, qualified leads, and bookings would require separate evidence.

### Simulated Funnel Example

<img src="images/02-simulated-stand-interest-funnel.png" alt="Simulation only. Of 100 fictional sessions, 60 reach the stand options and 18 click the lower WhatsApp button. The step-to-step rates are 60 percent and 30 percent." width="800">

The example uses **simulated data** throughout. Of 100 fictional sessions, 60 reach the stand options and 18 click the lower button. That gives step-to-step rates of **60%** and **30%**, and an overall click rate of **18%**. If verified event data showed a similar pattern, I would compare the journey by device before testing whether moving the button closer to the stand options helped.

## Sources and Limitations

- The charts distinguish the Excel-based prospect counts from the fictional website sessions. Only aggregate workbook counts are included. The campaign report and presentation provide context. Confirming their account or participation totals would require the underlying records.
- The proposed events illustrate how the fair could measure website interest. GA4 implementation and observed funnel performance remain future work.
