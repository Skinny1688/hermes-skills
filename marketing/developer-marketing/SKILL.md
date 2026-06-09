---
name: developer-marketing
description: Marketing strategy for developer audiences and developer tools. Covers developer SEO, developer advocacy, conference talks, live coding, podcasts, building in public, technical content strategy, and competing with documentation sites. Use when asked about marketing to developers, dev tool marketing, DevRel, developer advocacy, developer SEO, error message content strategy, technical tutorials, or building developer community.
metadata:
  version: 1.0.0
  category: marketing
---

# Developer Marketing

This skill combines developer SEO and developer advocacy into a comprehensive guide for marketing to developer audiences. Developers search differently, evaluate differently, and convert differently than general audiences. This skill adapts marketing strategies accordingly.

---

## Understanding Developer Audiences

### How Developers Search

Developers search with precise technical intent—error messages, API questions, "how to X in Y language" queries. They bounce immediately from thin content and respect sites that actually solve problems.

**Query patterns:**
- Error messages (often copy-pasted verbatim)
- "How to [action] in [language/framework]"
- "[Tool A] vs [Tool B]"
- "[Concept] tutorial"
- "[Library] [specific function] example"

**Behavioral signals:**
- High bounce rates on superficial content
- Long dwell time on genuinely helpful pages
- Multiple tabs open comparing solutions
- Quick scroll to code examples
- Immediate exit if content doesn't match query intent

### Search Intent Categories

1. **Troubleshooting**: Developer has an error, needs a fix
2. **Learning**: Developer wants to understand a concept
3. **Evaluating**: Developer comparing tools or approaches
4. **Implementing**: Developer needs working code examples
5. **Reference**: Developer needs quick syntax or API lookup

---

## Developer SEO

### Keyword Research for Developers

Technical long-tail keywords have lower volume but extremely high intent.

**Research approaches:**

1. **Mine your support channels** — Extract questions from tickets, Discord/Slack community, GitHub issues
2. **Stack Overflow mining** — Search for questions mentioning your tool category; note exact phrasing
3. **Google Search Console analysis** — Find queries you rank positions 5-20 for; identify question-based queries
4. **Competitor content gaps** — What questions do competitors' docs not answer?

### Error Message SEO

Error messages are SEO gold—developers copy-paste them directly into search.

**Strategy:**
1. Create dedicated pages for common errors
2. Use exact error text in titles and H1s
3. Include the full error message early in content
4. Provide the actual fix, not generic troubleshooting
5. Add related errors users might also encounter

**Content structure for error pages:**

```
Title: [Exact Error Message] - How to Fix

## The Error
[Full error message and where it appears]

## Quick Fix
[The solution that works in most cases]

## Why This Happens
[Brief technical explanation]

## Other Solutions
[Alternative fixes for edge cases]

## Related Errors
[Links to similar issues]
```

### Competing with Official Documentation

**Where docs often fail:**
- No "why" explanations, just "what"
- Missing real-world examples
- No troubleshooting guides
- Outdated content
- No comparative context

**Your opportunities:**
- "Getting started with X" tutorials that hold your hand
- "X vs Y" comparison content (docs never compare)
- Migration guides between versions or tools
- Real-world implementation examples
- Common gotchas and how to avoid them

### Content Formats That Rank

**How-To Guides** — Structure with prerequisites, quick version, step-by-step, complete example, common issues.

**Comparison Content** — Be genuinely objective; include actual code comparisons; cover specific use cases where each wins; mention your tool's limitations honestly.

**Tutorial Series** — Identify a topic cluster, create pillar content, build supporting content for specific subtopics, interlink strategically.

### Technical SEO for Developer Sites

- Use semantic HTML for code (`<code>`, `<pre>`)
- Add language hints for syntax highlighting
- Ensure code is actual text, not images
- Test that code actually works
- Minimize JavaScript for documentation pages
- Ensure content loads without JS when possible
- Clear hierarchy (Guides > Category > Specific Topic)
- Breadcrumbs for navigation
- Proper canonical tags for versioned docs
- XML sitemaps for large doc sites

---

## Developer Advocacy

### Conference Talks

**The winning CFP formula:**
```
Specific Problem + Unique Angle + Clear Takeaways = Accepted Talk
```

**Title patterns that work:**
- "How I X" — "How I Reduced Deploy Time by 80%"
- "X in Y Minutes" — "Kubernetes Security in 15 Minutes"
- "Beyond X" — "Beyond Console.log: Modern Debugging"
- "X for Y" — "GraphQL for REST Developers"
- "Lessons from X" — "Lessons from 1000 Production Outages"

### Live Coding & Demos

**The 10-3-1 Rule:**
- Run your demo **10 times** in practice
- Have **3 checkpoints** you can jump to if stuck
- **1 backup** (video recording of it working)

**Pre-demo checklist:**
- Close unnecessary apps
- Clear browser history/tabs
- Notifications OFF
- Font size: 24pt+ for terminal, 20pt+ for editor
- Git stash/branch for clean starting point
- Environment variables ready

### Podcast Guesting

**Pitch template:**

```
Subject: Guest Idea: [Specific Topic] for [Podcast Name]

Hi [Host Name],

I've been listening to [Podcast] for [time] — loved your episode on [specific episode].

I'd love to come on and talk about [specific topic]. Here's the angle:

[2-3 sentences on what you'd discuss and why it matters to their audience]

A bit about me:
- [Relevant credential 1]
- [Relevant credential 2]
- [Link to past podcast/talk]

Would this be a fit?

[Your name]
```

### Building in Public

**What to share:**
- Progress: "Shipped X today, here's what I learned"
- Challenges: "Stuck on X, tried Y and Z, here's what worked"
- Decisions: "Why we chose X over Y"
- Metrics: Revenue, users, growth (transparently)
- Behind scenes: Team, process, tools
- Learnings: "Mistake we made and how we fixed it"

**What NOT to share:**
- Customer data, team conflicts, security details, competitor attacks, venting

### Developer Twitter/X Playbook

- **Value content** (60%): Tips, tutorials, insights
- **Engagement** (20%): Replies, retweets with commentary
- **Personal** (10%): Behind-the-scenes, personality
- **Promotion** (10%): Your product, talks, content

---

## Measuring Developer Marketing Impact

### Metrics That Matter

- Organic traffic to documentation and guides
- Rankings for target technical queries
- Time on page for tutorial content
- Search Console impressions for error message queries
- GitHub referrals from technical content
- Talk attendees and feedback scores
- Social: followers, engagement rate, reach
- Traffic spikes from content/talk/podcast
- "How did you hear about us?" responses

### Metrics to Interpret Carefully

- **Bounce rate** — Developers often find answer and leave; that's success
- **Pages per session** — For reference content, one page is fine
- **Conversion rate** — Long attribution windows for developer tools

---

## Common Mistakes

1. **Writing for search engines, not developers** — Keyword-stuffed content that doesn't actually help
2. **Ignoring search intent** — Ranking for queries but not matching what developers actually need
3. **Thin content** — Short posts that don't provide real value
4. **Outdated examples** — Code that no longer works in current versions
5. **No unique value** — Rehashing what official docs already cover
6. **Hard selling** — Developers distrust obvious marketing; earn trust first

---

## Budget and Resources

### Minimum Viable Approach
- **Time investment**: 5-10 hours/week for content creation
- **Tools needed**: Google Search Console (free), basic keyword research tool
- **Timeline**: 3-6 months to see meaningful organic growth

### Scaled Approach
- Dedicated technical content writer
- SEO tools subscription (Ahrefs, Semrush)
- Content management system optimized for docs
- Regular content audits and updates

---

## Task-Specific Questions

1. What developer community does your target audience belong to?
2. What technical questions come up most in support tickets?
3. Do you have Search Console access?
4. What content format resonates with your audience? (tutorials, comparisons, API docs)
5. What's your current developer community engagement level?

---

## Related Skills

- **seo-audit**: For comprehensive SEO auditing
- **copywriting**: For writing individual content pieces
- **cro**: For optimizing pages for conversion