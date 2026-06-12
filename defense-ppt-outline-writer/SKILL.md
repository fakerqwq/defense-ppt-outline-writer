---
name: defense-ppt-outline-writer
description: Read a complete thesis, proposal, opening report, research plan, or `.docx`/PDF/Markdown academic document and turn it into a concise, structured defense presentation outline plus an oral defense script. Use when the user asks to extract full document content, split it by structure, preserve original wording as much as possible, compress into PPT-ready pages, organize major points with nested subpoints/paragraph hierarchy, or write a defense speech/script from the resulting outline.
---

# Defense PPT Outline Writer

## Core Promise

Transform a full academic document into two deliverables:

1. A PPT-ready content outline with page-by-page structure, concise key content, major points and nested subpoints.
2. A defense script that explains the same structure clearly for reviewers.

Preserve original sentences, original phrases, and original table-of-contents items whenever possible. Do not paraphrase academic claims just to make them sound smoother.

## Workflow

1. **Read the full source**
   - For `.docx`, PDF, or other Office files, use an appropriate document extraction skill/tool before outlining.
   - Extract headings, body paragraphs, lists, tables, citations, and the document table of contents if present.
   - Keep the source file path and create outputs near the source unless the user specifies another folder.

2. **Recover the document structure**
   - Identify title, author/info, research background, research significance, literature review, research gap, theories/concepts, research content, research questions, research thinking/path, methods, thesis framework, innovation, difficulties/feasibility, plan, references, and any project-specific sections.
   - Preserve the source order unless the user asks for a different defense logic.

3. **Compress for a defense PPT**
   - Reduce content volume while retaining key claims, key phrases, and original wording.
   - Combine pages when content naturally belongs together, for example:
     - research background into 1-2 pages ending in the core research question;
     - research significance into one page with theoretical/practical levels;
     - literature review into 1-2 pages with category summaries and an overall summary;
     - theory, research content, methods, and plan into compact structured pages.
   - Use paragraphs when complete point-by-point splitting would make the logic feel fragmented.
   - Use nested structure when a major point contains sub-explanations.

4. **Write the PPT outline**
   - Output page-by-page content in Markdown.
   - Each page must have a clear title.
   - Use the labels `PPT正文：` and then the exact content.
   - Keep page content immediately usable for slide design.
   - Prefer this hierarchy:
     - page title;
     - short lead paragraph or framing sentence;
     - major point;
     - nested subpoints or paragraph explanation;
     - final takeaway/core question when needed.

5. **Write the oral script**
   - Use the approved outline as the source of truth.
   - Explain each slide in reviewer-facing language.
   - Keep the script aligned with slide order.
   - The script may add natural transitions, but the core claims should remain faithful to the outline and source document.

6. **Validate**
   - Check that every major source section has either been included or intentionally omitted with a reason.
   - Check that the outline is not a raw paste of the source.
   - Check that original sentences/phrases were preserved in the slide body.
   - Check that the script follows the same page order and does not introduce unsupported claims.

## Output Files

When writing files, use these default names unless the user specifies otherwise:

- `<source-stem>_PPT内容划分_层级段落版.md`
- `<source-stem>_答辩讲稿_层级段落版.md`

If an earlier version exists, create a descriptive new version rather than overwriting user-approved work unless explicitly requested.

## Detailed Contract

For exact formatting rules, page planning patterns, and quality checks, read:

- `references/output-contract.md`
