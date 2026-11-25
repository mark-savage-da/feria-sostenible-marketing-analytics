# Feria Sostenible | Exhibitor Research and Marketing Analytics

Feria SOStenible brought together businesses and visitors interested in sustainability in Panama City. This case documents my exhibitor research during my advertising and marketing internship at Onegona and presents a separate proposal for measuring exhibitor interest on the event website.

## My contribution at Onegona

I researched prospective exhibitors and strategic partners and organized the information in Excel. I used a pivot table to group prospects and support the team's outreach prioritization. This case does not claim that I contacted those prospects, measured campaign performance, or generated bookings. Internal lists, contact details, and agency files are not included.

## Portfolio extension: measuring exhibitor interest

**Business question:** Among visitors who reach the public Products page, how many see the stand options and then click the WhatsApp contact button?

The [Products page](https://feriasostenible.com/productos/) lists stand options and displays a bottom **Escríbenos** WhatsApp button. I would measure the following steps in order, within the same session:

| Step | Proposed event | Illustrative sessions | Share of previous step |
|---|---|---:|---:|
| Opened the Products page | `products_view` | 100 | — |
| Saw the available-stands section | `stand_options_view` | 60 | 60% |
| Clicked the bottom WhatsApp button | `exhibitor_whatsapp_click` | 18 | 30% |

All counts are simulated. I would record each step once per session and distinguish the bottom button from the WhatsApp shortcut at the top of the page. In this example, 18% of Products-page sessions reach the final step. A click indicates contact intent, not a message sent, a qualified lead, or a reservation.

The lower step-to-step rate in this example is from stand options to the contact button. Before recommending changes, I would check that the events fire at the right time, then compare mobile and desktop sessions. If the pattern holds, I would test placing the contact button closer to the stand list.

## Sources and limitations

- [Ciudad del Saber event listing](https://ciudaddelsaber.org/eventos/feria-sostenible) provides public event context for August 2–3, 2025.
- [Feria SOStenible Products page](https://feriasostenible.com/productos/) documents the stand options and WhatsApp contact path used in the proposed measurement plan.
- No live analytics, campaign results, or internal records are included. The event names above describe proposed tracking, not an implementation.
