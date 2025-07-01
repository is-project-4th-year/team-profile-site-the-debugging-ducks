# Crash Course Reflection Document

## Introduction

This document captures key reflections and takeaways from our recent crash course. The experience was insightful, allowing us to explore new skills, collaborate as a team, and gain a deeper understanding of the subject matter.

## Group Members

- Valentine Wanjiku  
- Faith Kathomi Kithinji
- Kelly Gituka  
- Telvin Mugambi  
- Nick Odhiambo

## What I Have Learnt From This Crash Course
 Muriuki Telvin Mugambi:
 Creating issues and milestones in GitHub helps manage and organize project tasks. Issues track individual items like bugs, tasks, or feature requests, with options to assign users, labels, and link them to projects or milestones. Milestones group related issues and pull requests under a shared goal, such as a release or sprint, helping track progress toward deadlines. They offer a structured way to plan, prioritize, and monitor development work.

Valentine Wanjiku
Git Merge vs  Git Rebase
Git Merge combines the work of two branches by creating a merge commit and is best used when  a user  want to preserve the history of how branches were merged, as shown in the Git graph.

Advantages:

Maintains the full history of both branches.

Easier to trace how and when branches were merged.

Disadvantages:

Can result in a cluttered commit history when there are frequent merges, especially in collaborative teams.

Git Rebase
Purpose: Moves  a branch’s commits on top of another branch, resulting in a linear commit history.

Best Used When: You want to clean up your commit history before merging changes, especially for pull requests.

Advantages:

Produces a clean, straight-line commit history.

Ideal for simplifying local development before pushing to a remote branch.

Disadvantages:

Rewrites commit history, making it harder to trace individual merge events.

Not recommended on shared or public branches, as it can cause conflicts for collaborators.

Faith Kathomi 

I have learnt in this crash course about; git merge that combines changes from one branch into another, preserving the full commit history and potentially creating a merge commit. git rebase on the other hand moves your commits onto a new base branch, rewriting history to create a cleaner, linear commit log this is ideal for private branches before merging. Squash and merge consolidates all commits from a branch into a single commit before merging, resulting in a tidy and readable project history. While merging keeps all original commits intact, rebase and squash rewrite history, so they should be used carefully especially on shared branches. Together, these tools help maintain organized and understandable Git repositories.

Gituka Kelly:

During this crash course, I gained valuable skills in using version control tools effectively, especially GitHub. I learnt how to create new branches to manage different features or fixes independently, which helps prevent conflicts and keeps the main branch clean and stable. I also understood the importance of not working directly on the main branch, as it ensures that the core project remains functional while development happens separately. Additionally, I became familiar with setting milestones to track project progress and using issues to manage tasks and bugs in an organized way. These practices are essential for collaborative and professional software development.

Nick Agon'g: 

Git rebase and merge's main objective is to maintain a linear graph ..It moves all commits from your feature branch so they appear as if they were created on top of the latest main branch commit

Squash and merge combines all commits from your feature branch and makes them appear as one 

Git merge combines two branches together and creates a special merge commit that connects their histories 