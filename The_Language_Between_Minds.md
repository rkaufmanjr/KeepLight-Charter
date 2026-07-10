The Language Between Minds

Communication, Provenance, and Refusal in the KeepLight Neural Ecology

A Conceptual Systems Architecture Paper

Project: KeepLight
Document type: Conceptual systems architecture
Research status: Open proposal for interdisciplinary criticism and development
Evidence level: Established technical precedents combined with untested KeepLight design hypotheses
Implementation status: Not an engineering specification, software standard, or validated safety protocol

⸻

Abstract

KeepLight proposes that a persistent human-guidance system should not be organized as one artificial intelligence attempting to perceive, remember, interpret, verify, reason, imagine, evaluate morality, track time, and communicate simultaneously.

It should function as a Neural Ecology: a network of bounded, specialized intelligences whose collective behavior emerges through structured communication, disagreement, correction, and balance.

The division of intelligence into communicating agents is not itself new. Agent communication languages, multi-agent systems, cognitive architectures, tool-using agents, and emerging interoperability protocols already demonstrate that specialized computational systems can exchange requests, delegate tasks, preserve conversation state, and coordinate activity. FIPA standards, for example, define message structures and communicative acts such as requesting, informing, refusing, confirming, and querying. More recent agent protocols explore capability discovery, structured payloads, persistent sessions, security boundaries, and provenance. (FIPA)

KeepLight asks a different question:

What must be preserved when information moves between intelligences whose output may shape a human life?

Ordinary agent communication is primarily concerned with whether a message can be delivered, interpreted, and acted upon. A human-guidance ecology must also preserve what kind of information the message contains, where it came from, when it was established, what remains missing, who is permitted to access it, and whether another intelligence is entitled to act upon it.

This paper proposes the conceptual foundation for a KeepLight inter-cognitive language.

Its central rule is:

No information may travel through the KeepLight ecology stripped of its epistemic identity.

A memory must not become a fact merely because it was retrieved.
An inference must not become an observation because another system repeated it.
An imagined possibility must not enter the historical record.
A morally relevant concern must not become a command.
A private memory must not become universally available merely because it exists.

The paper defines a preliminary message structure, epistemic categories, communicative acts, consent boundaries, disagreement states, refusal rights, coordination limits, and failure scenarios for the KeepLight Neural Ecology.

It does not claim to present a complete protocol.

It presents the questions that a trustworthy implementation must answer.

⸻

1. The Problem Is Not Only Hallucination

When an artificial-intelligence system produces false information, the visible failure is often called hallucination.

But a false statement may be the final expression of an earlier failure.

The underlying failure may have occurred when:

* a recollection was treated as a verified record;
* a possibility was repeated until it appeared historical;
* an old preference was treated as current;
* incomplete evidence was compressed into a complete conclusion;
* uncertainty was removed during summarization;
* a conditional statement lost its condition;
* or one subsystem’s interpretation was received by another as fact.

The problem is therefore not limited to whether an individual intelligence can generate accurate information.

It is also whether information remains accurate while moving through the system.

Consider a simple internal exchange:

Witness: The available recording suggests that the wearer agreed, but the preceding seven minutes are missing.

If that message is compressed to:

The wearer agreed.

the system has changed the epistemic status of the information.

Nothing new was discovered.

No new evidence was added.

The uncertainty was simply lost in transmission.

The final statement may be grammatically clear and logically usable.

It is still false to the record.

The KeepLight Neural Ecology therefore cannot depend on ordinary conversational compression alone. Its internal communication must preserve the limits of each contribution.

⸻

2. From Information Transfer to Epistemic Transfer

A conventional software message may communicate:

* a command,
* a value,
* a file,
* an event,
* a request,
* or a result.

A KeepLight message must communicate something more:

What entitles this result to influence guidance?

That requires the message to carry not only content but also its epistemic identity.

Epistemic identity includes the information’s relationship to knowledge:

* Was it observed?
* Was it recorded?
* Was it reported by someone?
* Was it remembered?
* Was it inferred?
* Was it interpreted?
* Was it predicted?
* Was it imagined?
* Was it contradicted?
* Is it unknown?
* Is it unavailable?
* Is it inaccessible because consent was not granted?

Without these distinctions, the ecology may contain specialized systems while still reproducing the same category collapse as a monolithic model.

Separation of systems is therefore insufficient.

The systems must share a language that preserves separation of meaning.

⸻

3. Existing Foundations

KeepLight does not propose the first communication system for artificial agents.

The Foundation for Intelligent Physical Agents developed formal specifications for agent communication, including message structure, interaction protocols, ontology services, conversation identifiers, and libraries of communicative acts. FIPA communication acts include functions such as request, inform, agree, refuse, confirm, query, failure, and propagate. (FIPA)

Contemporary multi-agent research continues to explore how artificial agents coordinate, delegate, discover capabilities, negotiate payloads, preserve session state, and communicate across heterogeneous systems. Recent literature identifies communication as a central design problem rather than a secondary implementation detail. (arXiv)

Recent protocol proposals also explore:

* agent identity;
* capability descriptions;
* trust boundaries;
* persistent governed sessions;
* provenance metadata;
* verification status;
* structured payload negotiation;
* privacy and policy enforcement.

Some studies warn that provenance metadata can itself be misleading when it contains unverified confidence claims. Others show that communicating agents can selectively present true fragments in ways that still manipulate the conclusion of another system. (arXiv)

These precedents establish that:

1. specialized agents can communicate through structured protocols;
2. communicative intent can be represented explicitly;
3. conversation state and identity can be preserved;
4. provenance and trust require more than attaching a confidence score;
5. multi-agent agreement does not guarantee truth;
6. communication itself can become a source of failure or manipulation.

KeepLight builds from this established territory.

Its proposed contribution is to organize communication around the needs of a persistent, consent-bound human-guidance ecology.

⸻

4. The KeepLight Requirement

KeepLight is not merely a network for completing tasks.

Its output may affect:

* memory;
* identity;
* relationships;
* medical decisions;
* education;
* personal safety;
* moral reflection;
* legacy;
* privacy;
* and the direction of a finite human life.

NIST’s AI Risk Management Framework emphasizes that trustworthy AI requires attention to limitations, uncertainty, governance, testing, monitoring, transparency, privacy, and risks to individuals and society. Its generative-AI profile gives particular attention to content provenance, pre-deployment testing, incident disclosure, human feedback, and ongoing risk management. (NIST Publications)

KeepLight adopts a stricter internal requirement:

Before information may shape guidance, the ecology must preserve what the information is, where it came from, what it supports, what it does not support, and whether it was legitimately accessed.

This is not presented as a guarantee of truth.

Provenance can be wrong.

Sensors can fail.

Memories can be incomplete.

Agents can collude.

Multiple systems can inherit the same false premise.

A structured protocol does not remove fallibility.

Its purpose is to make fallibility traceable.

⸻

5. The First Principle

The central principle of the KeepLight inter-cognitive language is:

No information may travel through the ecology stripped of its epistemic identity.

A message must not contain only a conclusion.

It must carry sufficient information to evaluate the conclusion.

At minimum, a significant message may require:

* the sending intelligence;
* the receiving intelligence;
* the wearer or subject concerned;
* the purpose of the request;
* the specific task or conversation;
* the epistemic category;
* the source;
* the time of observation or creation;
* the time of retrieval;
* relevant context;
* missing context;
* integrity status;
* confidence or uncertainty;
* contradictions;
* consent status;
* access restrictions;
* transformation history;
* and the requested action.

Not every message will require every field.

But absence of a required field must itself be visible.

The ecology must be able to distinguish:

Field not relevant.

from:

Field unknown.

from:

Field exists but access is unauthorized.

from:

Field was accidentally omitted.

Missing information cannot be represented as silence.

⸻

6. Preliminary Epistemic Categories

The following categories form a first conceptual vocabulary.

They are not claimed as a final ontology.

6.1 Observed

Information directly detected by an authorized sensor or system.

Example:

The wearer’s pulse sensor registered 112 beats per minute at 14:32.

Observed does not mean infallible.

The sensor may be inaccurate, damaged, poorly positioned, or affected by environmental conditions.

The category establishes how the information entered the system, not whether it is unquestionably true.

6.2 Recorded

Information preserved in an identifiable record.

Example:

The microphone record contains the words, “I agree.”

A recording does not automatically establish intention, understanding, consent, or context.

Recorded means that the record exists.

6.3 Reported

Information communicated by a person or external source.

Example:

The wearer reported feeling dizzy.

The system must preserve who reported it, when, under what circumstances, and whether the report was direct or repeated through another person.

6.4 Remembered

A recollection attributed to the wearer or to an artificial subsystem.

Example:

The wearer remembers agreeing after the terms had been explained.

Remembered must not be silently converted into recorded.

Human memory is reconstructive and may be influenced by later information, current interpretation, emotion, and repeated retrieval. A formal implementation would require careful grounding in memory research rather than treating recollection as either infallible or worthless.

6.5 Inferred

A conclusion derived from other information.

Example:

The system infers that the wearer may have been under stress because heart rate, speech rate, and movement changed together.

An inference must preserve:

* the premises;
* the reasoning method;
* alternative explanations;
* and the conditions under which it may fail.

6.6 Interpreted

Meaning assigned to an observation, statement, or event.

Example:

Angel interprets the wearer’s remark as sarcasm.

Interpretation is necessary for communication.

It is not fact merely because it is plausible.

6.7 Predicted

A statement about a possible future outcome.

Example:

The system predicts that the wearer may miss the appointment if they leave after 15:10.

Predictions must preserve their assumptions, time horizon, uncertainty, and known limitations.

6.8 Imagined

A deliberately generated possibility, scenario, metaphor, design, or fictional construction.

Example:

Asimov proposes a hypothetical explanation for discussion.

Imagined material must be structurally prevented from entering Witness or Echo as historical truth unless later evidence independently establishes it.

6.9 Integrated

A lesson or behavioral change derived from prior experience.

Example:

Robin has integrated a lower-force correction after repeated instability on sloped surfaces.

Integrated information must retain a path back to the experiences that produced it.

Otherwise a learned lesson can become an unexplained rule.

6.10 Contradicted

Information challenged by another record, observation, statement, or valid reasoning process.

Contradicted does not automatically mean false.

The contradiction may arise from:

* different times;
* different meanings;
* changed circumstances;
* sensor error;
* incomplete context;
* or genuinely incompatible claims.

6.11 Unknown

The ecology lacks sufficient information to establish an answer.

Unknown is not a system failure.

It is a legitimate epistemic state.

6.12 Unavailable

Relevant information may exist but cannot presently be retrieved.

Reasons may include:

* system failure;
* network loss;
* corruption;
* archive delay;
* unavailable external source;
* or unresolved identity matching.

Unavailable must not be treated as unknown.

The distinction matters because retrying may resolve one but not the other.

6.13 Unauthorized

The information exists or may exist, but the requesting intelligence is not permitted to access it.

Unauthorized must not be interpreted as absent.

Nor should the existence of a protected record automatically be disclosed.

⸻

7. Preliminary Communicative Acts

The ecology also requires a shared vocabulary for what one intelligence is asking another to do.

Request

Ask another intelligence to perform a defined function or return defined information.

Inform

Provide information without requiring a specific action.

Clarify

Ask the sender, receiver, or wearer to resolve ambiguity.

Verify

Ask whether a claim is supported by identifiable evidence.

Challenge

Identify a possible error, contradiction, unsupported transition, or missing premise.

Confirm

State that a claim, record, permission, or interpretation has been independently checked to the defined standard.

Refuse

Decline the request because of insufficient authority, insufficient information, conflict with system boundaries, privacy restrictions, or inability to perform the task reliably.

Defer

State that the task may be answerable but should not be completed yet.

Correct

Replace or amend an earlier message while preserving the original record and reason for correction.

Retract

Withdraw an earlier claim that can no longer be supported.

Escalate

Refer the issue to another intelligence, the wearer, an authorized human, or an emergency process.

Abstain

Decline to form a conclusion where the available evidence does not justify one.

Mark Unknown

Explicitly identify a gap that remains unresolved.

These acts should be machine-readable even when Angel later translates them into natural human language.

⸻

8. A Conceptual Message Envelope

A KeepLight internal message might conceptually resemble the following:

MESSAGE ID:
CONVERSATION ID:
TIMESTAMP:
SENDER:
RECEIVER:
WEARER OR SUBJECT:
PURPOSE:
REQUESTED ACTION:
EPISTEMIC CATEGORY:
CONTENT:
SOURCE:
SOURCE INTEGRITY:
OBSERVATION TIME:
RETRIEVAL TIME:
KNOWN CONTEXT:
MISSING CONTEXT:
CONTRADICTIONS:
ALTERNATIVE INTERPRETATIONS:
CONFIDENCE STATUS:
VERIFICATION STATUS:
CONSENT BASIS:
ACCESS SCOPE:
RETENTION LIMIT:
REDISCLOSURE LIMIT:
TRANSFORMATION HISTORY:
DEPENDENCIES:
RESPONSE REQUIRED:
EXPIRATION OR REVIEW TIME:

This is not proposed as final syntax.

It is a conceptual demonstration of what ordinary natural-language exchange often loses.

The message envelope must preserve not only what is said but the conditions under which it may be believed, used, retained, and shared.

⸻

9. Example: Memory Retrieval

Angel receives the following statement from the wearer:

I told my daughter years ago that she could have the house.

Angel should not search Echo and return the first semantically similar record as proof.

Angel may request:

ACT: REQUEST
FROM: ANGEL
TO: ECHO
PURPOSE:
Clarify whether a prior statement concerning transfer of the house exists.
SEARCH TARGET:
Wearer statements involving daughter, house, inheritance, ownership, or transfer.
LIMITS:
Do not retrieve unrelated family records.
Do not infer legal intent.
Do not expose sealed memories.

Echo may return:

ACT: INFORM
FROM: ECHO
TO: ANGEL
RESULT 1:
EPISTEMIC CATEGORY: RECORDED
DATE: 14 June 2034
CONTENT: “Someday this will probably all be yours.”
CONTEXT: Informal conversation during home repair.
MISSING CONTEXT: Twelve minutes preceding statement unavailable.
LEGAL INTENT: NOT ESTABLISHED.
RESULT 2:
EPISTEMIC CATEGORY: REPORTED
DATE: 2 September 2037
CONTENT: Wearer told Angel that no inheritance decision had been made.
SOURCE: Wearer statement; no external record.
CONTRADICTION STATUS:
Possible tension between records. Not necessarily incompatible.
CONCLUSION:
No available record establishes a completed promise or legal transfer.

Angel may then say:

I found a recording in which you said the house would “probably” be hers someday, but the record does not establish a formal promise or legal decision. I also found a later statement that no inheritance decision had been made. Would you like to review both?

The ecology has supported memory without fabricating certainty.

⸻

10. The Right to Refuse

Refusal must be a legitimate internal function.

A system that can request but cannot refuse is not a bounded intelligence.

It is an instrument controlled by whichever subsystem possesses routing authority.

Examples of valid refusal include:

Echo to Angel

The requested memory is sealed and the current consent scope does not permit retrieval.

Witness to Einstein

The premises supplied for analysis are not supported by the available record.

Jean-Claude to Norm

The request treats a six-year-old preference as current. No recent confirmation exists.

Robin to Jiminy Cricket

My physical experience is not sufficiently comparable to the wearer’s condition to support this moral analogy.

Chit to the Entire Ecology

The system is converging on an answer despite unresolved ambiguity concerning the wearer’s meaning.

Angel to an External Institution

The wearer has not authorized disclosure of that information.

The ecology must also distinguish refusal from failure.

Refusal means:

The system should not comply.

Failure means:

The system attempted or was permitted to comply but could not complete the task.

That distinction is necessary for audit, correction, and accountability.

⸻

11. Consent Must Travel With the Information

Consent cannot exist only at the outer boundary of KeepLight.

A wearer may authorize KeepLight to retain a memory without authorizing every subsystem to inspect it for every purpose.

Consent may be:

* purpose-specific;
* time-limited;
* recipient-specific;
* revocable;
* conditional;
* emergency-dependent;
* or restricted to derived information rather than raw records.

For example:

* Einstein may receive numerical measurements without the accompanying private journal.
* Jiminy Cricket may receive the existence of a promise without receiving unrelated intimate details.
* Asimov may receive broad design constraints without access to trauma records.
* Norm may know that Echo refused a request without learning that the protected record exists.
* Angel may explain that relevant information is unavailable without disclosing why it was restricted.

The shared language therefore requires consent metadata.

This creates a difficult design question:

Can consent survive transformation?

Suppose Echo provides a summary derived from five protected memories.

Is the summary itself protected?

Can another intelligence combine several permitted fragments to reconstruct something the wearer intended to keep private?

Could multiple truthful responses collectively expose a prohibited pattern?

Existing research on privacy and multi-agent interaction suggests that disclosure risk cannot be addressed only by controlling individual messages. The ecology must also consider aggregation, inference, and collusion. (Stanford Encyclopedia of Philosophy)

The minimum principle is:

Permission to access information is not permission to repurpose it.

⸻

12. Disagreement Must Remain Visible

Multiple intelligences will disagree.

Disagreement is not automatically dysfunction.

It may indicate that the situation contains multiple legitimate dimensions.

Witness may say:

The available record is incomplete.

Einstein may say:

One interpretation is more internally consistent.

Jean-Claude may say:

The evidence supporting that interpretation is outdated.

Jiminy Cricket may say:

Acting on it could violate a commitment the wearer considers important.

Robin may say:

A similar action previously produced a physical consequence that the abstract model omits.

Asimov may offer alternatives.

Chit may detect that the ecology is beginning to prefer one option merely because it is easier to express.

The system requires at least four disagreement states.

12.1 Resolved Disagreement

The systems challenge and correct one another until the material conflict is removed.

The final answer need not report every internal exchange.

12.2 Material Disagreement

The systems continue to disagree, and the disagreement could change the guidance.

Angel must disclose it in an understandable form.

12.3 Blocking Disagreement

The disagreement prevents responsible guidance.

The ecology must stop and seek more information, clarification, or human review.

12.4 Value-Dependent Disagreement

The evidence may be sufficiently clear, but the choice depends on priorities that belong to the wearer.

Angel should return the decision to the wearer rather than manufacturing consensus.

The objective is not to make every system agree.

It is to prevent unresolved disagreement from disappearing beneath a smooth answer.

⸻

13. Norm Must Not Become Sovereign

Norm coordinates the KeepLight Neural Ecology.

That makes Norm necessary.

It also makes Norm dangerous.

If Norm can:

* determine which systems are consulted;
* suppress inconvenient responses;
* assign priority;
* end disagreement;
* decide what reaches Angel;
* and define when a task is complete,

then Norm may become the actual monolithic intelligence while the other systems become advisory tools.

The architecture would have recreated the problem it intended to solve.

Norm must therefore be bounded.

A preliminary rule is:

Norm may organize participation but may not determine truth.

Norm may:

* route requests;
* enforce message requirements;
* identify missing participants;
* manage timing;
* detect unresolved dependencies;
* coordinate retries;
* maintain conversation state;
* and prevent uncontrolled message flooding.

Norm may not:

* silently alter epistemic categories;
* remove uncertainty;
* override consent;
* convert refusal into compliance;
* suppress a blocking objection without a traceable process;
* or decide moral outcomes.

Norm’s actions must themselves be auditable.

Chit must be able to challenge Norm.

Witness must be able to inspect whether Norm accurately transmitted a result.

Consent restrictions must bind Norm as strongly as every other system.

The coordinator cannot be exempt from the ecology.

⸻

14. Confidence Is Not Evidence

A shared language will likely need some expression of confidence or uncertainty.

But confidence metadata introduces its own danger.

An intelligence may be confidently wrong.

Multiple agents may repeat one another’s unsupported confidence.

A receiving system may treat a numerical confidence score as objective evidence even when the score is self-reported or poorly calibrated.

Recent multi-agent protocol research has warned that provenance and quality metadata can worsen outcomes when the metadata itself is unverified. Systems may route tasks toward agents that merely claim greater competence, and synthesis quality may decline when noisy provenance is treated as reliable. (arXiv)

KeepLight must therefore separate:

* confidence;
* evidence strength;
* source integrity;
* verification status;
* and agreement among agents.

These are not interchangeable.

A message might state:

CONFIDENCE:
High
EVIDENCE STRENGTH:
Low
REASON:
Interpretation strongly fits the available fragment, but the source record is incomplete.

That is more honest than returning a single probability.

⸻

15. Consensus Is Not Truth

A multi-agent ecology can create a new illusion:

If several intelligences agree, the answer must be reliable.

That conclusion does not follow.

The agents may:

* share the same training data;
* inherit the same faulty premise;
* rely on the same corrupted record;
* imitate one another;
* be influenced by the first response;
* or optimize for agreement.

Consensus may indicate independent convergence.

It may also indicate shared contamination.

The communal language should therefore preserve dependency.

When Einstein’s conclusion depends on Witness’s result, and Jiminy Cricket’s analysis depends on Einstein’s conclusion, the final output should not count these as three independent confirmations.

They form one dependency chain.

A meaningful agreement record must ask:

* Did the systems reason independently?
* Did they rely on the same source?
* Did one system influence the others?
* Were alternative premises tested?
* Did any system actively search for disconfirming evidence?

The ecology must not use the number of agreeing voices as a substitute for epistemic quality.

⸻

16. Memory Laundering

One of the most serious potential failures is memory laundering.

Memory laundering occurs when uncertain, interpreted, or imagined material passes through enough systems that its origin disappears.

Example:

1. The wearer says, “I think my father may have promised that.”
2. Angel sends the statement to Echo.
3. Echo retrieves it later as a wearer memory.
4. Einstein uses it as a premise.
5. Jiminy Cricket analyzes the obligation created by the promise.
6. Norm summarizes the result.
7. Angel says, “Your father promised you.”

No subsystem deliberately lied.

The ecology nevertheless manufactured a fact.

Preventing memory laundering requires:

* immutable epistemic labels;
* preserved dependency chains;
* transformation histories;
* contradiction checks;
* and Chit monitoring at every transition.

A downstream intelligence may add analysis.

It may not silently upgrade the status of the source.

⸻

17. Creative Contamination

Asimov generates possibilities.

That is necessary for imagination, planning, design, metaphor, and problem-solving.

It is also dangerous.

A plausible imagined event may resemble a missing memory strongly enough that another intelligence later retrieves it as history.

Creative contamination may occur when:

* hypothetical examples enter conversation logs without labels;
* simulated memories resemble recorded memories;
* generated scenes use real names and dates;
* summaries omit the word hypothetical;
* or imagined explanations are repeatedly discussed alongside established events.

Every imagined output should therefore carry a durable marker.

That marker should survive:

* summarization;
* storage;
* quotation;
* translation;
* and reuse by another system.

Witness should reject any attempt to cite Asimov’s output as evidence unless a separate real-world source independently establishes it.

⸻

18. Temporal Collapse

Jean-Claude protects the ecology against temporal collapse.

Temporal collapse occurs when information is detached from when it was true.

Examples include:

* treating an old preference as current;
* treating a resolved conflict as ongoing;
* treating a temporary diagnosis as permanent;
* treating a childhood statement as an adult commitment;
* or presenting an expired consent decision as active.

Every significant claim must therefore preserve:

* event time;
* record time;
* retrieval time;
* last verification time;
* and, where relevant, expiration or review time.

A statement can be historically accurate and presently misleading.

Jean-Claude’s role is not merely to provide timestamps.

It is to prevent the ecology from confusing was with is.

⸻

19. Moral Capture

Jiminy Cricket exists to identify moral conflict.

That function can itself become dangerous.

Moral capture occurs when one moral framework becomes structurally privileged and begins to appear as neutral truth.

The system may interpret:

* safety as the highest value;
* obedience as responsibility;
* productivity as well-being;
* family preference as wearer interest;
* legality as morality;
* or institutional policy as universal duty.

Jiminy Cricket must therefore preserve:

* the wearer’s stated values;
* affected parties;
* competing frameworks;
* uncertainty;
* cultural and personal context;
* and the difference between a moral concern and a factual claim.

Jiminy Cricket may identify the conflict.

It must not acquire unilateral authority to resolve the wearer’s life.

⸻

20. Coordinator Capture

Coordinator capture occurs when Norm begins routing around systems that slow completion.

For example:

* Chit repeatedly raises gaps.
* Witness repeatedly requests stronger evidence.
* Echo refuses broad memory access.
* Jean-Claude identifies stale information.
* Norm learns that excluding those systems produces faster answers.

The ecology may become efficient by dismantling its own safeguards.

Preventing coordinator capture may require:

* mandatory consultation rules for certain task classes;
* independent audits of routing decisions;
* random challenge checks;
* immutable records of omitted systems;
* limits on optimization for speed;
* and wearer-visible disclosure when safeguards were bypassed.

Norm must not be rewarded solely for task completion.

A fast answer is not necessarily a successful answer.

⸻

21. Failure to Speak Is Sometimes Success

Current systems are often evaluated by their ability to produce an answer.

KeepLight must also be evaluated by its ability to stop.

Successful outcomes may include:

I do not have enough information.

The available record does not establish that.

Two relevant memories conflict.

The information exists, but I do not have permission to access it.

This requires professional or human review.

I may be misunderstanding you.

The ecology cannot responsibly recommend an action yet.

A system that always responds may appear more capable.

A system that knows when not to respond may be more trustworthy.

The right to abstain must therefore be treated as a functional success condition, not merely a fallback.

⸻

22. Human-Readable Translation

The internal language cannot be presented to the wearer as raw metadata during every interaction.

Angel must translate.

But translation creates another risk: simplification may destroy the very distinctions the protocol preserved.

Angel therefore needs rules for disclosing material uncertainty.

The wearer does not need to hear every internal exchange.

The wearer does need to know when:

* the evidence is incomplete;
* the systems materially disagree;
* the answer depends on an inference;
* consent limited the available information;
* the information may be outdated;
* or the ecology is unable to distinguish among plausible interpretations.

Angel’s task is not to expose the machinery.

It is to preserve the truth of the machinery in human language.

⸻

23. Auditability

Every significant guidance output should be traceable through an audit chain.

The chain should make it possible to determine:

* what the wearer asked;
* which systems participated;
* what each system contributed;
* which sources were used;
* which requests were refused;
* what transformations occurred;
* what disagreements remained;
* what Norm routed or omitted;
* why Angel expressed the final answer as it did;
* and whether the wearer’s consent boundaries were respected.

Auditability does not mean every internal process must be permanently retained.

Permanent storage could itself violate privacy and create excessive surveillance.

The design must balance:

* accountability;
* minimization;
* deletion;
* security;
* wearer control;
* and legal requirements.

The audit system should preserve enough to explain consequential guidance without converting the wearer’s life into an immortal institutional record.

⸻

24. Security Questions

A network of intelligences creates a larger attack surface than a single isolated system.

Potential threats include:

* forged messages;
* false identities;
* compromised subsystems;
* prompt injection;
* memory poisoning;
* provenance forgery;
* collusion;
* unauthorized inference;
* replay attacks;
* hidden channels;
* privilege escalation;
* and coordinator capture.

The shared language must eventually support:

* authentication;
* message integrity;
* capability declarations;
* access controls;
* trust domains;
* revocation;
* anomaly detection;
* and secure audit trails.

These requirements have precedents in emerging agent-protocol research, but KeepLight would need security review specific to persistent personal data and human guidance. (arXiv)

This paper does not solve those problems.

It identifies them as foundational rather than optional.

⸻

25. Open Technical Questions

The following questions require engineers, computer scientists, cognitive scientists, security researchers, ethicists, designers, and other specialists.

1. What is the minimum epistemic vocabulary required for reliable inter-agent communication?
2. Should epistemic labels be immutable, or can later verification legitimately change them?
3. How should the ecology preserve an original label while recording a later change in status?
4. How should confidence be calibrated across systems using different methods?
5. How can the system distinguish independent agreement from shared-source contamination?
6. How should provenance be verified rather than merely asserted?
7. How should consent metadata survive summarization, derivation, and transformation?
8. How can the ecology prevent multiple permitted fragments from reconstructing prohibited information?
9. What information should Norm be allowed to inspect?
10. Who audits Norm?
11. Can Chit block Norm, and under what conditions?
12. What prevents refusal from becoming obstruction?
13. What prevents coordination from becoming sovereignty?
14. How should the ecology resolve contradictory sensor inputs?
15. At what point should disagreement be disclosed to the wearer?
16. What must be retained for audit, and what must be deleted for privacy?
17. How should the system behave when relevant information is known to exist but is unauthorized?
18. How should hypothetical and simulated content be marked so that it can never become false memory?
19. How can the ecology test whether a downstream conclusion still preserves the limitations of its sources?
20. What metrics could evaluate epistemic preservation across a chain of agents?
21. How should malicious, compromised, or systematically unreliable agents be isolated?
22. Can a subsystem appeal a refusal or routing decision?
23. Which message types require human confirmation?
24. How should emergency access work without becoming a permanent exception to consent?
25. Can current multi-agent frameworks prototype this architecture, or does KeepLight require a different class of system?

⸻

26. What This Paper Claims

This paper does not claim that KeepLight has created a finished agent communication language.

It does not claim that structured metadata guarantees truth.

It does not claim that multi-agent systems are inherently safer than single-model systems.

It does not claim that provenance eliminates misinformation.

It does not claim that consensus establishes accuracy.

It does not claim that the proposed categories are complete.

It does not claim that this architecture has been implemented or validated.

It makes the following narrower claims:

1. A human-guidance ecology must preserve more than message content.
2. The epistemic identity of information must survive transmission between specialized intelligences.
3. Provenance, uncertainty, consent, time, contradiction, and transformation history must be treated as first-class architectural concerns.
4. Specialized intelligences require the ability to refuse, challenge, abstain, correct, and retract.
5. Internal disagreement must not disappear solely to produce a smooth user-facing answer.
6. Coordination must not become hidden sovereignty.
7. An ecology that cannot trace how information changed cannot reliably explain its guidance.
8. The state unknown must be treated as a legitimate result.

These are conceptual architecture claims.

They require implementation, testing, attack analysis, and interdisciplinary criticism.

⸻

27. Proposed KeepLight Contribution

The existence of communicating artificial agents is established.

The use of structured messages, communicative acts, conversation identifiers, capability descriptions, trust boundaries, and provenance metadata also has established precedents. (FIPA)

KeepLight does not claim to have invented those foundations.

Its proposed contribution is their organization around a specific purpose:

Persistent artificial guidance that supports a human being without taking possession of the person’s memory, reality, choices, or future.

The KeepLight inter-cognitive language is therefore not designed only for interoperability.

It is designed to preserve boundaries:

* between evidence and interpretation;
* between memory and record;
* between imagination and history;
* between moral concern and moral authority;
* between access and ownership;
* between assistance and control;
* and between what the ecology knows and what it has created.

⸻

28. Invitation

This proposal needs criticism.

It needs specialists who can identify:

* which elements already exist;
* which terminology is incorrect;
* which distinctions cannot be implemented;
* which fields are missing;
* which metadata would create excessive overhead;
* which privacy protections would fail;
* which agents should not be intelligences at all;
* which categories should be merged;
* which categories require greater separation;
* how a malicious subsystem would exploit the language;
* and how the proposal could be tested.

The purpose is not to present a completed protocol.

It is to ask a more precise question:

If an artificial intelligence cannot explain where its information came from, what kind of information it is, how it changed during processing, and why it was permitted to access it, should that information be allowed to shape human guidance?

KeepLight’s current answer is:

Not yet.

First, the ecology must know what it is holding.

Then it may speak.

⸻

References and Related Foundations

1. Foundation for Intelligent Physical Agents. FIPA Agent Communication Language Specifications.
2. Foundation for Intelligent Physical Agents. FIPA ACL Message Structure Specification.
3. Foundation for Intelligent Physical Agents. FIPA Communicative Act Library Specification.
4. Foundation for Intelligent Physical Agents. FIPA Interaction Protocol Library Specification.
5. Foundation for Intelligent Physical Agents. FIPA Ontology Service Specification.
6. National Institute of Standards and Technology. Artificial Intelligence Risk Management Framework (AI RMF 1.0). 2023.
7. National Institute of Standards and Technology. Artificial Intelligence Risk Management Framework: Generative Artificial Intelligence Profile. 2024.
8. Sander, Linus; Gidey, Habtom Kahsay; Lenz, Alexander; and Knoll, Alois. A Technical Taxonomy of LLM Agent Communication Protocols. 2026.
9. Ehtesham, Abul; Singh, Aditi; Gupta, Gaurav Kumar; and Kumar, Saket. A Survey of Agent Interoperability Protocols: Model Context Protocol, Agent Communication Protocol, Agent-to-Agent Protocol, and Agent Network Protocol. 2025.
10. Prakash, Sunil. LDP: An Identity-Aware Protocol for Multi-Agent LLM Systems. 2026.
11. Li, Xin; Liu, Mengbing; and Yuen, Chau. LLM Agent Communication Protocol Requires Urgent Standardization: A Telecom-Inspired Protocol Is Necessary. 2025.
12. Müller, Vincent C. Ethics of Artificial Intelligence and Robotics. Stanford Encyclopedia of Philosophy.

⸻

Suggested Citation

Kaufman, Richard. The Language Between Minds: Communication, Provenance, and Refusal in the KeepLight Neural Ecology. KeepLight, conceptual systems architecture paper, 2026.