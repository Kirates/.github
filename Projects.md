## **`Budget tracking app`**
It seems like all the budgetting apps I can find are missing some feature. Why don't I create one the has all features to go with it. Use cashbook as a UI design guide
        1. Cashbook uses the concept of books to seperate expenses. How about we use tags instead so that expense tagged with what it was
        2. Dashboard: Cashbook misses a dashboard feature. Let's implement it.
        3. Veiws: Use daily, weekly and monthly veiws to give users finer breakdown of their spending behavior
        4. Projection: allow users to project how much they intend to spend overall and also in various books/tags/categories and track how well they are sticking to it.
        5. Budget: allow users to allocate a budget at the start of every month and help monitor how well they are doing.
        6. Notifications and reminders: Remind user at the times they usually make purchases to enter them 
        7. Summaries: Summarize users' spendings across the day, week, month and year for them.
        8. Contributions: Certain items are not used up in a single month. Help users set small contributions aside towards it every month so that they don't have to buy it at a go. For this they can set the money aside physically and use the app to track how much is set aside for each item.
        9. Export to excel image and pdf feature
        10. share a certain book in excel or image format
        11. Budget progression and predictions
        12. Help users determine when they are consistently overspending in a certain category and what the ideal amount to allocate for that category.
        13. Inflow: while the user has a fixed budget they are spending allow them the enter inflows. For instance if they a bonus from work or cash gift from some where.
        11. Group wallets? like cashbook?

## **`Spellchecking VS code extension`**
Vs code is not always about code. sometimes you need to write json files and so on
This extension if not already in existence should allow you to spell check the currently open file.


## **`Routime`**

Imagine yourself cought in a routine. This could be an exercise routine, work-rest cycles, etc. You want to do an activity `A` for `X0` minuetes and then rest for `Y0` minutes and repeat. After `N` repetitions, you wish to switch to activity `B` with `X1` and `Y1` actvity-rest cycles just like `A`. Sometimes, there is short rest between `A` and `B` other time none. This is the core of the `Routime`. It gives you the flexibility to time anything anyhow you want it.

        1. Subroutines: these are smaller routines that are part of a bigger routine. Eg: Two sets of pushups during a workout routine.

        2. Routine: This is the main activity going. Eg: A workout session.

        3. You can choose if the rest period should be part of the total activity time or seperated. Eg: If you are doing pushups for 1min, do you prefer the 5sec breaks are within the one minute or 1min + plus 5sec break time, you call.

        4. Each routine should have activity, activity time, break time, repetitions, and whether break is within the activity time.

        5. The activity time for each routine could be a subroutine. A subroutine is a full routine on its own and has same properties as a normal routine, just been called under another routine.

        6. Total time for  a routine, should be computer summing the time for all subroutines, activity times, and breaks together.

        7. For monotonous routines, you can set the tone for the end of activity and start of rest period. And vice-versa.

        8. If a routine has many subroutines, we should use voice anouncements to announce the start and end of on subroutine to the next.

        9. Instructions: You can include written/voice instructions as to how the routine should be done. This can also be announce at the start.

        10. Basically, you can make the app into a virtual coach announce your next activity and time you.

        11. Research did not produce any exact matches in existence.

## **`RobustQuiz`**

Google forms, microsoft forms, etc, all have some element of quizzing in them. However, when I looked at Gforms, it was adequate for making a full form experience.
Some the features that are missing are as follows:

        1. Instead of one correct as with google forms, how about we could provide options that are all answers but have different degrees of correctness.
        A typical usecase is when you are creating an assessment in which you don't want to assess the participants peronality and biasisd instead of straightup right and wrong answers, then you could options within which their chioce tells more about their personlity. In this case, you could assign different points to the various options.

        2. How about you want to access people's leanings without points, say you want to label as something based on their choices. Eg: for every person who chooses option C is a gamer and that is all you want.

## **`ImmortalMe:`**

When people have funerals and events, there are numerous ways to share and distribute the pictures in the moment. However, is there a way to perserve those memories for posterity?
Will the unborn generation ever see grandma's funeral pictures? How about here wedding? ImmortalMe provides this avenue where you can save selected photos from an event and add some information the will help others find it later centuries to come.

    1. How many max photos should be allowed?
    2. What types of events should we consider aside funerals.
    3. should we allow videos?

    4. What will be the cost implications of storing data for such a long time?

    5. How will we price it? One time payment?

    6. Can people add info for others? for instance a dead relative who had a profile they were alive.

## **`Multi-languaguage translation:`**

Using google translate, provide a website that allow translation of a word, sentence, paragraph, or entire passage to be translated into all supported languages at a go.

    1. Explore the google translate API to see how to use it for one language.

    2. The explore the possibility of using it for muliple languages.

    3. Is it possble to translate to muliple languages by one API call?

    4. If not, how would you build custom means to do that?

## **`Twi translation:`**

Design a language translation model.

    1. Study natural language translation techniques to build a model for existing languages.

    2. Train the model on basic Twi.

    3. Use the Twi bible as a test data set to train the model more accurately.

    4. Contact the bible society and other Twi publishers to obtain twi data for publishing.

    5. It Possible to provide one to one mapping of words from english to twi? For instance many proper nouns will never change form. So, providing the translation straight will speed up the learning process a lot.
