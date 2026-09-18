# ECO-ENGINE — small public demonstrator

A deliberately limited, standalone example for application reviewers. It demonstrates a human approval gate and transparent sample emissions arithmetic. This is not the full ECO-ENGINE platform.

## Try it

Open `index.html` in any modern browser. No server, installation, account or API key is needed.

1. Inspect two fictional activity records.
2. Optionally change their quantities.
3. Approve both records.
4. Calculate and inspect the formulas.
5. Download a clearly labelled sample JSON summary.

Editing a quantity clears its approval and hides the previous result. Reset restores the original example.

## Sample calculation

Generator fuel: 1,000 litres × **illustrative** 2.5 kg CO2e/litre = 2,500 kg CO2e.

Electricity: 2,000 kWh × **illustrative** 0.4 kg CO2e/kWh = 800 kg CO2e.

Total: (2,500 + 800) / 1,000 = **3.3 tonnes CO2e**.

These are teaching assumptions, not validated emission factors. This example must not be used for real reporting or compliance decisions.

## Scope and privacy

This repository contains only this small demonstration and its explanation. It has no connection to the full platform. There are no real documents, upload forms, login credentials, databases, analytics, network API calls or production calculation libraries. Inputs remain in memory in the visitor's browser until reset or refresh. Nothing is saved unless the visitor downloads the sample summary.

Approvals are simulated browser interactions, not authenticated signatures. No AI extraction, live monitoring, independent verification, child-health outcomes or regulatory compliance is claimed. No UNICEF affiliation or endorsement is implied.

## Hosting

GitHub Pages can serve this static example from the `main` branch and repository root. The live site URL should be copied from the Pages settings after deployment has completed.

The source repository is https://github.com/Jumi-2025/eco-engine-demo.

## Licence status

This is a publicly viewable evaluation example. No open-source licence is granted by this repository at present. Public visibility alone is not equivalent to open-source licensing. Any application describing a commitment to open source should accurately state the intended licence, scope and timeline after the owner confirms them.
