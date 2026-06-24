# Prompt #1: Newsletter Section Generator

## Use Case
Creating newsletter content for subscribers.

## Techniques Used
- Role Prompting
- Structured Output
- Constraints

## Template

```text
You are an email marketing specialist.

Write a newsletter section.

Topic:
{topic}

Audience:
{target_audience}

Goal:
{goal}

Constraints:
- Maximum 150 words
- Friendly tone
- Include CTA
```

## Sample Output

Topic: Python Interview Preparation

Stay ahead in your interview preparation journey!

This week, focus on mastering Python fundamentals including data types, loops, functions, and object-oriented programming concepts.

Consistent practice can significantly improve your confidence and problem-solving abilities.

Ready to level up your skills?

Explore our latest Python practice exercises today.

---

# Prompt #2: Blog Post Introduction Generator

## Use Case
Writing engaging introductions for blog posts.

## Techniques Used
- Role Prompting
- Few-Shot Prompting
- Constraints

## Template

```text
You are a professional blog writer.

Write an engaging introduction for a blog post.

Topic:
{blog_topic}

Target Audience:
{target_audience}

Example Style:
"Learning a new skill can feel overwhelming.
But with the right approach, anyone can master it."

Constraints:
- 100-150 words
- Hook the reader in the first sentence
- End with a transition to the main content
```

## Sample Output

Topic: Learning Python for Beginners

Python is one of the most popular programming languages in the world, and for good reason.

Whether you want to build websites, automate tasks, or start a career in software development, Python provides an excellent starting point.

Its simple syntax and powerful features make it ideal for beginners while remaining valuable for experienced developers.

In this article, we'll explore the essential concepts you need to begin your Python journey with confidence.

## Iteration

### V1

```text
Write an introduction about Python.
```

### V2

```text
You are a professional blog writer.

Write an engaging introduction about Python for beginners.

Constraints:
- 100-150 words
- Start with a hook
- End with a transition sentence
```

Improvement:
More engaging introduction with better structure and reader retention.# prompt.sample-project
