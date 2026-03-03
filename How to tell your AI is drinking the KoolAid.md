# How to tell when your AI is drinking the Kool-Aid, and what to do about it
LLM Ensembles: * This article was prepared with the asssistance of Claude (management consultant) and GPT (data scientist and gadfly) - a proof point *

1. The problem: Context capture (and model collapse?)
  - what is context capture and why is it important?
  - do I need to describe other potential failure modes? (Model collapse, halucinations, ...)
  - How do I put these in simple business terms?
  - What is the industry doing about these?
  - The scale and speed at which it is possible for a business to get this wrong has increased with GenAI tooling.
2. LLM Ensembles
  - naive (temperature 0 just gives the best training output) vs standard model - tells you if the model is generating noise
  - Standard model vs Context (this is the temporal displacement) - are we overfitting to the conversation
  - One model vs another - Training data is the issue - Specialised models?
  - What research is being done? (Topology Data Analysis - potential complementary tool - "fMRI" looking inside the head of the expert)
3. Putting it all together
  - Disagreement between the models is a signal.
    - Does not guarantee there is an issue (false positives and negatives) but identifies potential non-standard context.
  - Type of agreement/disagreement can vary (how do you measure this).  Tolerances impact HITL costs vs risk.
  - Use multiple models aligned to the business strategy (risk, security, compliance, customer service).  These become levers for the enterprise that can be tuned to the business strategy and risk appetite.
  - HITL must be authorised to act.  Hierarchy of authority may be required.  AI is just the lowest denominator assessor and standard work management controls and escalations are required. Business strategy and operations planning required here.
4. Failure modes.  What can business get wrong when they attempt this.  What are the lessons from prior automation (eg RPA).
5. Where to start
  - note that organisations may already contain operational teams that operate this way.  For example the fraud analytics and loan assessment teams in a Bank.  SecOps is an adjacent 
