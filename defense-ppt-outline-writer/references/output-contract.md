# Output Contract

## Content Preservation Rules

- Slide body text should be mostly source-derived: original sentences, original phrases, table-of-contents entries, and terms from the document.
- Page titles and structure labels may be concise organizational language.
- Do not invent data, literature categories, research questions, sample sizes, dates, or conclusions.
- If compression is necessary, cut secondary elaboration before changing wording.
- If wording must be shortened, prefer extracting a contiguous original phrase over rewriting.

## Outline Shape

Use this Markdown pattern:

```markdown
# <任务名或文档名>_PPT内容划分_层级段落版

说明：以下“PPT正文”尽量摘自《<源文件名>》原句、原文短语或原文目录条目；页面标题、层级标签和结构提示仅用于组织答辩结构。

## 第1页：<封面标题>

PPT正文：

<标题>

<副标题/开题报告/作者信息>

## 第2页：<页面标题>

PPT正文：

<引导段，尽量原句>

- <一级点，尽量原文短语或原句>
  - <二级展开，尽量原句>

<收束段，尽量原句>
```

## Recommended Defense Deck Flow

Adapt to the source, but this flow works for most opening defenses:

1. Cover
2. Research background: macro context and platform/problem context
3. Research background: relationship lines and core research question
4. Research significance: theoretical and practical levels
5. Literature review: foreign research categories and summary
6. Literature review: domestic research categories and overall summary
7. Research gap
8. Theoretical foundation and core concepts
9. Research content
10. Research questions
11. Research path/thinking, preferably flowchart-ready
12. Research methods
13. Thesis framework
14. Innovation points
15. Difficulties and feasibility
16. Research plan
17+. References

## Compression Patterns

- **Background**: two paragraphs plus 2-3 contrast cards; end with the core problem.
- **Significance**: two major sections, usually “理论层面” and “实践层面”.
- **Literature review**: show category list first, then summary; do not list every article unless it matters.
- **Research gap**: 3-4 major gaps; each gap gets 1-2 source-based explanations.
- **Theory**: one page; answer “用户在管理什么” and “用户依托什么进行管理” or equivalent conceptual questions.
- **Research content**: 4-6 modules; each module gets one short expansion.
- **Research path**: write as short flow nodes plus brief explanations.
- **Methods**: one page; each method has object/sample/function.
- **Framework**: use original chapter and subsection directory entries.

## Hierarchy And Paragraph Rules

- Use paragraphs when a claim needs continuity.
- Use bullets when the page contains parallel dimensions, categories, methods, or stages.
- Use nested bullets when a major point contains specific explanations.
- Avoid flattening all bullets into the same level.
- Avoid turning every sentence into a separate bullet.

## Script Shape

Use this Markdown pattern:

```markdown
# <任务名或文档名>_答辩讲稿_层级段落版

## 第1页：<页面标题>

各位老师好，我的开题题目是……

## 第2页：<页面标题>

这一页主要说明……
首先，……
其次，……
因此，……
```

Script requirements:

- Follow the PPT outline page order.
- Explain why the slide matters, not just read every word.
- Use reviewer-facing transitions: “这一页主要说明…”, “这里我想强调…”, “由此引出本文的核心问题…”.
- Do not add new unsupported claims.
- Keep each slide script proportional to its importance. Background/literature/research design can be longer; references can be brief or omitted unless the user asks to speak them.

## Quality Checklist

Before final delivery, report:

- Source file read successfully.
- Outline page count.
- Script page count or slide coverage.
- Whether major sections are covered.
- Whether references are included if requested.
- Any content omitted or merged and why.

If possible, run a text coverage check against the extracted source or the generated outline to ensure the script follows the approved outline.
