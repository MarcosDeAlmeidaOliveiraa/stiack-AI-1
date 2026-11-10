> For the complete documentation index, see [llms.txt](https://docs.stackai.com/llms.txt). Markdown versions of documentation pages are available by appending `.md` to page URLs; this page is available as [Markdown](https://docs.stackai.com/guides-and-quickstarts/workflow-builder.md).

# Workflow Builder

Workflow Builder connects inputs, processing steps, and outputs on a canvas. Use it when you need to control how information moves through an application.

These guides explain models, variables, structured outputs, routing, loops, reusable project calls, and code. They also cover files, audio, tables, memory, and triggers.

Use execution details to inspect the values each step receives and returns. Configure failure handling according to the behavior users need when a step cannot complete.

{% hint style="info" %}
Your working draft saves automatically as you edit. See [Autosave and concurrent editing](/technical-reference/releases-and-environments/autosave-and-concurrent-editing.md) to check the saved status, review detailed changes, and handle updates from another session.
{% endhint %}

### Guides in this section

* [First input to output workflow](/guides-and-quickstarts/workflow-builder/first-input-to-output-workflow.md)
* [Configure models and prompts](/guides-and-quickstarts/workflow-builder/configure-models-and-prompts.md)
* [Map variables and expressions](/guides-and-quickstarts/workflow-builder/map-variables-and-expressions.md)
* [Structured outputs and templates](/guides-and-quickstarts/workflow-builder/structured-outputs-and-templates.md)
* [Conditional and AI routing](/guides-and-quickstarts/workflow-builder/conditional-and-ai-routing.md)
* [Loops and reusable project calls](/guides-and-quickstarts/workflow-builder/loops-and-reusable-project-calls.md)
* [Compare the StackAI Project and Beta nodes](/guides-and-quickstarts/workflow-builder/compare-the-stackai-project-and-beta-nodes.md)
* [Code execution](/guides-and-quickstarts/workflow-builder/code-execution.md)
* [Document, image, and URL processing](/guides-and-quickstarts/workflow-builder/document-image-and-url-processing.md)
* [Audio input and output](/guides-and-quickstarts/workflow-builder/audio-input-and-output.md)
* [Tabular data workflows](/guides-and-quickstarts/workflow-builder/tabular-data-workflows.md)
* [Conversation memory](/guides-and-quickstarts/workflow-builder/conversation-memory.md)
* [Triggers and scheduled and event runs](/guides-and-quickstarts/workflow-builder/triggers-and-scheduled-and-event-runs.md)
* [Workflow debugging and node results](/guides-and-quickstarts/workflow-builder/workflow-debugging-and-node-results.md)
* [Error handling and fallback branches](/guides-and-quickstarts/workflow-builder/error-handling-and-fallback-branches.md)
* [Canvas organization](/guides-and-quickstarts/workflow-builder/canvas-organization.md)
* [AI assisted workflow editing](/guides-and-quickstarts/workflow-builder/ai-assisted-workflow-editing.md)


---

# Agent Instructions
This documentation is published with GitBook. GitBook is the documentation platform designed so that both humans and AI agents can read, navigate, and reason over technical content effectively. Learn more at gitbook.com.

## Querying This Documentation
If you need additional information that is not directly available in this page, you can query the documentation by asking a question.

Perform an HTTP GET request on the following URL with the `ask` and `goal` query parameters:

```
GET https://docs.stackai.com/guides-and-quickstarts/workflow-builder.md?ask=<question>&goal=<user_goal>
```

`ask` is the immediate question: it should be specific, self-contained, and written in natural language.
`goal` is what the user is ultimately trying to achieve, the reason they need the answer. Sharing it helps GitBook give you a better, more relevant answer. A goal is most helpful when it describes the outcome the user wants rather than restating the question. For example, with `ask=how do I create an API token`, a goal like `automate deployments from our CI pipeline` lets GitBook tailor the answer to that use case.

The response will contain a direct answer to the question and relevant excerpts and sources from the documentation.

Use this mechanism when the answer is not explicitly present in the current page, you need clarification or additional context, or you want to retrieve related documentation sections.
