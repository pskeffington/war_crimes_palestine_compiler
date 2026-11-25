# Sources, Method, and Research Safeguards

## Inclusion rule

The primary incident dataset includes U.S. citizens or U.S. forces harmed by Israeli state actors in Palestine or Lebanon. A distinct historical category may include pre-state Zionist armed organizations, such as Irgun, only when the event is central to the project's history and explicitly labeled as pre-state. Incidents attributed to other actors are out of dataset scope and appear only in an exclusion note if needed to explain boundaries.

## Person categories

- **U.S. citizen:** citizenship supported by an official record, family statement reported by a credible source, or other documented evidence. Record dual citizenship where relevant.
- **U.S. service member:** service status at the time of incident must be sourced. Do not conflate with U.S. citizens serving in another country's forces.
- **U.S. government personnel / contractor:** record whether civilian, uniformed, employee, contractor, or local national; do not infer U.S. citizenship.
- **U.S.-linked victim:** U.S. family, residence, employer or community ties alone do not prove U.S. citizenship.

## Attribution categories

Use a concise value in the data field attribution_status:

- confirmed_actor: source establishes the actor at an organizational level; individual responsibility may remain unknown.
- officially_acknowledged: government or military acknowledges the operation/strike, while target or legality may be disputed.
- investigative_assessment: an inquiry or investigation attributes responsibility using its own stated standard.
- reported_allegation: family, witnesses, advocates or reporting attribute the act; corroboration remains incomplete.
- contested: materially different accounts remain unresolved.
- unknown: available evidence does not establish an actor.

Never infer individual guilt from organizational attribution. Name alleged individual perpetrators only where a credible source names them and mark the allegation's procedural status.

## Evidence grades

- **A — primary/official:** contemporaneous diplomatic or military record, court filing/judgment, original video or medical record reviewed with permission.
- **B — investigative:** method-transparent, independently reported investigation, forensic reconstruction, or UN fact-finding report.
- **C — reported:** credible news report, family testimony in reporting, or NGO documentation with sufficient attribution.
- **D — lead only:** later summary, unverified database, or incomplete citation; use to find better evidence, not as a standalone finding.

Grade applies to the source's support for a specific claim, not its overall reputation. For a consequential claim, seek independent corroboration and source material.

## Capture protocol

For each source, capture title, issuing author/institution, publication date, URL, access date (UTC), source type, relevant excerpt or page/paragraph, data version, and local archived copy where lawful and safe. Preserve the exact date range and denominator attached to casualty counts. Do not overwrite a source snapshot; append corrections and note when a dynamic page changed.

## Source and people safety

Do not scrape private accounts, bypass access restrictions, or collect personal data unrelated to the public-interest case. Do not publish addresses, private contact details, or source-identifying metadata. Seek informed consent for direct testimony, especially from bereaved families, minors, and people at risk of retaliation. Use secure storage for non-public records and restrict access. This public repository should contain only public-source material and approved, non-sensitive records.

## Legal language

“War crime,” “murder,” “terrorism,” “genocide,” and similar terms must be attributed to a named source, formal charge, or legal decision. Describe facts and evidentiary disputes separately from legal characterizations. Distinguish a criminal charge, warrant, inquiry finding, civil judgment, and final criminal conviction.

## Corrections

If a victim's citizenship, identity, date, location, actor or casualty count changes, update the CSV and matrix with a dated note explaining the prior entry, new evidence, and source. Never silently delete a disputed case; retain a correction trail without exposing protected information.
