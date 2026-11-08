# TODO – needforheat-diagnosis-software

Open work for this repository, distilled from the old NeedForHeat Trello board, including the discussions on the cards (paraphrased and regrouped) and from the 2026 maintenance review.

Items that touch several repositories are written out in full in one *lead* repository; the others list them with a link (→). Keep the details up to date in the lead repository only.

## Later: features and ideas

- [ ] <a id="ha-local"></a>**Run NeedForHeat Diagnosis locally on Home Assistant.** A local-first variant for early adopters: an HA add-on that reads the home's own history from Home Assistant, runs the physics-informed models and shows the learned heat signature and diagnosis in HA. A way to make physics-informed machine learning known to this group. Separate from the HA data source for campaigns.
