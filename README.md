# SoftwareDesignPrinciples

My favorite design principles are listed below. 
It's my personal opinion based on experience and work on real projects but not just copy pasted from the internets.

### TIME
Time is most valuable IT resource. Always keep in mind it.

### KISS 
Keep It Stupid Simple. If you could simplify your code - make it. Less code you have - less bugs you see, less time you spent on support and fix it. 
Time is most valuable IT resource. If you are creating somethong big and hard explained - be sure noone understand how it works, even youself. 
Sometime it could take even longer to write short code but it will safe your and your teammembers time to support/test it.

### Devil is in the Details:
![image](https://github.com/user-attachments/assets/fe7a5d67-531d-4376-91d3-107950db179d)
** Because I hate 'The'

### YAGNI
You ain’t gonna need it. Never spend your time for writing large number of features wich could probably never need.
Time is most valuable IT resource. Focus on busyness requirenments.

### DONT-BE-HURRY
Be careful, stay focused. Take your #TIME and think carefully about what changes you are making to the code. Review your code changes again and again before clicking commit & push. 

### FIX-ALL-SIMILAR
If you found a bug and fixed it - then try to think of where the similar places it could be too. Find sibling properties, methods, classes etc. 
If you skip this - you will come back here to fix one more and more similar bugs and you will lost your #TIME due to time is most valuable IT resource.

### CODE-REVIEW-MATTER
Let the team see and review your code. You could easily miss the mistake. 
Do not think you code - is the best ones, it almost each time wrong. Do not be lazy to make suggestions for improvement. 
If noone makes review of your code you are going deeper into your delusions and much harder to fix it.

### THINK-CRITICALLY
Suggest that you are wrong in first place. And try to find weak places in your code. Always apply the worst case circumstances and answer to yourself how code will behave.

### PREFER-ATOMIC
If you deal with multi-step operations which should be done as a single, try to do it atomically.
Noone process/tread should have ability to influence your data during first and last step.

### PYTHON-ZEN 
Copy pasted from internets but totally agree with that:
  - Beautiful is better than ugly
  - Simple is better than complex
  - Readability counts
  - If the implementation is hard to explain, it's a bad idea
  - If the implementation is easy to explain, it may be a good idea
  
### NAMING-MATTER
Always think about the name of your variables, function, parameter, class etc. It should be as possible clean, explaining, consistent with the related context and no typos in it. It will never includes plenty words 
  
### REMEMBER-BIG-O
Keep tracking of performance of your code: it should not do anything except you planned to do. The same calculations should not be performed multiple times if the result is the same and we could cache it on first calculation.
Think about complexcity of your algorithm - it could be simpler and faster if you try.

### DONT-REINVENT-THE-WHEEL
Try not to write the code which is not belong to business requirements. 
You need not to create StringUtils if it always done by Apache Common Utils. You need not create and close db connection if it done in Spring Jdbc.

### REMEMBER-THE-TEAM
When working in the team you have to keep in mind of:
  - Your changes could brake their changes
  - Their changes could brake your ones
  - Update branch to be aware of any changes
  - Share your ideas with the team and try to understand their ones
  
### WARNINGS-MATTER
Warnings never be without reasons on it. When you ignore just single #warning it will come back to you again sometime later and steel you #TIME to fix it. 
When you see huge amount of warning you are not able to find the most important ones.
  
### FORMAT-YOUR-CODE
Formatted code will never show irrelevant changes in your commit. It will let see less and only relevant code changes.
