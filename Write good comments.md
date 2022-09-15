# Should I comment everything?
Personally, most of my years of development involved describing every section of code with a descriptive comment. I found it makes following the logical flow of the method easier to understand, specially if you're looking for something and aren't sure where it is.

Another somewhat related benefit of writing descriptive comments, is that it forces you to pay attention to what you're actually doing with your code. There were many times where I realized my code wasn't doing what it should after writing a comment that described it.

Despite these benefits, experienced developers tend to prefer reading actual code instead of comments, specially since there's a risk of distracted developers changing code without looking at the comment, hurting readability considerably.

## What do I comment?
I recommend you write as many TODO comments as you need to describe the logic of what you need to do, then remove comments as you consider each section of code to be readable enough without it. This way you get the benefits of commenting but keep a relatively comment free codebase.

Keep in mind that if you're working on existing code, the answer might come from either the code that is already there, or from discussion with colleagues and managers.

# Write readable code
One thing everyone agrees on is that we want to write code that is understandeable. That is one of the main goals when developing, because whether it's you coming back to your own code 2 weeks later or a new joiner, the easier your code is to understand, the easier it is to expand/fix but most importantly the quicker it goes and the cheaper it is for your employer.

# Try to delete your comments
A good exercise to know how many of your comments should survive your commit/push, is to compare how readable your code is when you remove your comment. If removing the comment makes it hard to understand what a section of your code is doing, maybe you should move it to it's separate method. That way the name of the method itself describes what it's doing, and your original code becomes easier to read.

# Explaining why
I've read that the most logical comments to keep around are those that explain why you wrote the code. Figuring out what the code does is theoretically easy just by reading it, but knowing why it's there in the first place is not as straight forward. That increases the value of using comments to describe.
