## I used ChatGPT to write all the stuff he knows, and this is what he wrote:
# 👋 Hello, Internet. I'm Lucas.

```text
Username:       LucasLiNotFound4747
Species:        Human
Occupation:     Student / Programmer / Professional Bug Generator
Languages:      English + 中文 + occasionally keyboard smash
Main Language:  C++
Favorite Error: The one that disappears after changing absolutely nothing
Current Status: Probably coding something unnecessary
```

Welcome to my GitHub profile.

I'm **Lucas**, a student who likes programming, chess, websites, games, weird experiments, GitHub, programming languages, breaking things, fixing the things I broke, and occasionally creating things that nobody asked for.

I don't really have one specific type of project.

Sometimes I make a normal website.

Sometimes I make a chess engine.

Sometimes I make a chess variant where the pieces can be blasted across the board.

Sometimes I decide I want to investigate every programming language GitHub recognizes.

Sometimes I invent my own programming language.

And sometimes I spend an unreasonable amount of time trying to understand why one square on a checkerboard has somehow transformed into a rectangle.

Basically:

> **"Wait... can I make this?"**

is responsible for approximately 97% of my projects.

---

# 🧑‍💻 About Me

I'm interested in:

- 💻 Programming
- 🌐 Web development
- ♟️ Chess
- 🎮 Games
- 🤖 AI
- 🧠 Algorithms
- 🛠️ Building random tools
- 🧪 Programming-language experiments
- 🐛 Producing bugs
- 🔨 Destroying those bugs
- 🐛 Accidentally producing three replacement bugs
- 📦 GitHub
- 🌍 GitHub Pages
- 🦈 GitHub achievements
- 🧩 Making things that probably did not need to exist
- 🚀 Trying something simply because I want to know whether it works

I speak both **English and Chinese**, so my conversations/code-development process can occasionally look like:

```text
English English English English
English English
这个东西英文叫什么
English English English
C++
English
啊啊啊啊啊啊啊啊啊啊啊啊
fixed
```

This is normal.

---

# 💻 Programming

My main programming language is:

## C++

```cpp
#include <iostream>
using namespace std;

int main()
{
    cout << "Hello, GitHub!" << endl;
    return 0;
}
```

I use C++ for algorithm problems and programming practice.

My preferred C++ style is suspiciously specific.

I like:

```cpp
int firstDay = 1;
int totalDays = 30;

if (firstDay > 0) cout << totalDays << endl;
```

I generally prefer:

- `using namespace std;`
- `cin` and `cout`
- camelCase variable names
- spaces around operators
- readable but compact code
- global arrays when appropriate
- simple solutions
- no unnecessary comments
- no unnecessary blank lines
- no random line breaks
- braces placed consistently
- code that looks like a human wrote it
- code that actually ACs

Especially the last one.

### My relationship with C++

```text
Lucas:      I understand this.
C++:        Segmentation fault
Lucas:      I no longer understand this.
```

---

# 🌎 Other Languages

C++ may be my main language, but programming languages are interesting to me in general.

I've explored or messed around with things including:

```text
C++
Python
HTML
CSS
JavaScript
TypeScript
Go
Swift
Kotlin
WebAssembly
...and various other things I probably clicked on because GitHub showed them.
```

Learning about **R** also produced one of programming's greatest conversations:

```text
Person: What programming language do you know?
You: R.
Person: Are what?
You: R.
Person: Yeah, the languages ARE what?
You: THE LANGUAGE IS R.
```

Go is not much better:

```text
Person: What programming language do you know?
You: Go.
Person: Okay.

*leaves*
```

Programming language naming is a beautiful disaster.

---

# 🧪 I Also Invented a Programming Language

Because apparently using existing programming languages wasn't enough.

I have experimented with designing my own language called:

# Cossert

Cossert has syntax that is intentionally... Cossert.

For example, some of its ideas include things like:

```text
FINALANSER(...)
```

for returning a value.

Loop control includes:

```text
SKIPTIS
```

for `continue`, and:

```text
FRGETABTIT
```

for `break`.

Random values can use syntax like:

```text
PICKARANDOM(FROM(value)TO(value)W/O(value))
```

because apparently:

```cpp
rand()
```

wasn't emotionally expressive enough.

Lists can look like:

```text
HAV A LIST "name" LIKE [items]:
```

and items can be removed with:

```text
TAKITOUT
```

Cossert is the kind of language where the compiler and programmer may both need emotional support.

---

# ♟️ Chess

I like chess.

A lot.

Enough that "make a chess website" eventually stopped meaning normal chess.

I've experimented with:

- Human vs AI chess
- Stockfish vs Stockfish
- Chess engines
- Browser chess
- Chess variants
- Multi-board games
- Chess vs Xiangqi
- Chess vs Checkers
- Chess vs Go
- Completely unreasonable combinations of board games

One important rule:

## Capturing the king is NOT checkmate.

If I'm implementing chess, I want actual chess logic:

```text
King is attacked
      ↓
Can king/player escape?
   ↙             ↘
 YES              NO
 ↓                ↓
Continue      CHECKMATE
```

Legal moves shouldn't leave your own king in check.

The king doesn't just stand there waiting to be eaten like:

```text
♚: well this is unfortunate
```

---

# 💥 Blast Chess

At some point, normal chess apparently became insufficient.

So I experimented with **Blast Chess**.

The idea:

> What if instead of simply moving pieces...
>
> ...you could BLAST THEM?

Pieces can be launched in directions using energy.

The winning condition can involve:

- actual checkmate
- or blasting the opponent's king off the board

Which means chess went from:

```text
1. e4 e5
2. Nf3 Nc6
```

to approximately:

```text
KNIGHT
ENERGY: 87%
DIRECTION: NORTHEAST

FIRE
```

This is what chess was missing.

Probably.

---

# 🤖 Stockfish Adventures

I've also experimented with putting **Stockfish** into browser-based chess projects.

This introduced me to:

```text
JavaScript Workers
WebAssembly
UCI
GitHub Pages
local HTTP servers
file paths
MIME types
and suffering
```

One of the important discoveries was:

```text
stockfish.js exists       ✅
stockfish.wasm exists     ✅
browser loads JS          ✅
WASM file is empty        ❌
entire universe collapses ❌
```

Eventually:

> **Stockfish UCI ready.**

Those four words can produce unreasonable amounts of happiness after debugging WebAssembly.

---

# 🎲 Checkers

I have also built/experimented with checkers.

At one point the goal was:

> **Make an unbeatable checkers AI.**

Which was going surprisingly well until another problem appeared:

THE BOARD SQUARES STARTED CHANGING SIZE.

Some squares became thin rectangles.

Some became giant rectangles.

The pieces distorted the board.

This resulted in the extremely technical debugging report:

> **"WHAT IS THIS BUG?!?!?!?1?!"**

Eventually the board stopped violating Euclidean geometry.

Then I was winning a game.

And accidentally clicked:

> **New Game**

There are bugs caused by code.

And then there are bugs caused by the programmer's finger.

---

# 🌐 Websites

I like making browser projects because you can go from:

```text
random idea
```

to:

```text
actual thing running in Chrome
```

surprisingly quickly.

I've made or experimented with things such as:

- Games
- Chess sites
- Checkers
- Translators
- Random launchers
- Profile pages
- Utility websites
- Location comparison tools
- AI-related prototypes
- Weird interactive experiments
- GitHub Pages projects

I particularly like projects that can run as:

```text
index.html
```

because there is something deeply satisfying about an entire project being:

> open file → thing works

---

# 📡 GitHub Pages

GitHub Pages has been both extremely useful and occasionally extremely confusing.

The basic journey:

```text
Create repository
      ↓
Upload index.html
      ↓
Enable GitHub Pages
      ↓
Wait
      ↓
Refresh
      ↓
Why is this a directory listing
      ↓
Fix something
      ↓
Refresh
      ↓
IT WORKS
```

I've used GitHub Pages for browser games, Stockfish experiments, and various other static projects.

---

# 🐙 My GitHub Arc

For a while, I wanted a GitHub achievement.

GitHub responded with:

```text
No.
```

Then I stopped particularly caring about getting an achievement.

GitHub immediately responded with:

# 🏆 YOLO

Apparently the secret achievement strategy was:

> Stop trying.

YOLO was unlocked after merging a pull request without review.

Then I learned about another achievement:

# 🤠 Quickdraw

Requirement:

```text
Open Pull Request
      ↓
Close it within 5 minutes
```

Naturally, the question became:

> "Wait, does 5 seconds count?"

Yes.

Yes it does.

So:

```text
PR created
↓
approximately three molecules of time pass
↓
PR closed
↓
🤠 GITTY UP!
```

Quickdraw unlocked basically immediately.

GitHub now has permanent evidence that I murdered my own pull request at extraordinary speed.

---

# 🦈 The Pull Shark Situation

After YOLO and Quickdraw came the next target:

# Pull Shark

Concept:

```text
PR #1 → MERGED
PR #2 → MERGED
        ↓
       🦈
```

Unlike Quickdraw:

```text
Close ❌
Merge ✅
```

And unlike Quickdraw, which apparently has the reaction time of a gaming monitor, Pull Shark may occasionally behave like:

```text
GitHub Department of Sharks

Your application is currently being processed.

Estimated processing time:
3–700 business days.
```

So if a shark eventually appears here:

Mission accomplished.

---

# 🍴 Forks, Contributors, and the Moment GitHub Finally Made Sense

At some point I needed to understand:

> What actually IS a contributor?

Which led to the GitHub permission rabbit hole.

The important discovery:

```text
Contributor ≠ Collaborator
```

A random person doesn't need permission to destroy your `main` just to contribute.

Instead:

```text
Your repository
      ↓
They FORK it
      ↓
Their repository
      ↓
They modify their copy
      ↓
Pull Request
      ↓
You inspect it
      ↓
Merge / Reject
```

Which is excellent because otherwise open source would operate like:

```text
Welcome to my project!
Here are the keys.
Please don't delete everything.
```

---

# ⭐ Star vs 🍴 Fork

Another useful distinction:

```text
⭐ STAR
=
"I like this / save this for later."

🍴 FORK
=
"I want my own GitHub copy to work on."
```

A fork isn't just a fancy bookmark.

And a star doesn't clone the entire repository into your account.

GitHub terminology makes much more sense once somebody actually explains what the buttons DO.

---

# 📁 `.gitignore`

`.gitignore` is basically the file that says:

> Git, please pretend these things don't exist.

For example:

```gitignore
__pycache__/
*.pyc
node_modules/
.env
```

GitHub provides templates for different development environments.

One particularly important discovery:

> The `.gitignore` template named **AL** does NOT mean **ALL LANGUAGES**.

It means the actual programming language **AL**.

This matters when you're staring at a giant alphabetical dropdown and wondering whether GitHub has conveniently provided:

```text
AL = ALL
```

It has not.

GitHub has no:

```text
EVERYTHING
ALL LANGUAGES
PLEASE IGNORE ALL THE JUNK
```

template.

Tragic.

---

# 🗃️ AllOfGithubLanguages

At some point I became interested in the idea of having a repository containing examples of lots of languages GitHub can recognize.

Which creates an interesting `.gitignore` problem:

```text
Which language template should I choose?

C++?
Python?
Node?
Go?
Rust?
Swift?

Answer:
uhhhhhhhhhhhhh
```

For something intentionally containing many different languages, a custom `.gitignore` makes much more sense than pretending one ecosystem represents everything.

---

# ⛏️ Minecraft / Eaglercraft

I also like Minecraft-related stuff.

This eventually led into the wonderful rabbit hole of extremely old Minecraft versions.

Including discussions like:

> What is the oldest Minecraft version?

and:

> How do we beat Minecraft in `rd-132211`?

Answer:

You don't.

There isn't exactly an Ender Dragon patiently waiting inside a 2009 development build.

Early Minecraft is fascinating because looking at it now feels like discovering an archaeological site where somebody eventually decided:

> You know what this block game needs?

> **Everything.**

---

# 🧱 Early Minecraft Weirdness

Old Minecraft versions contain things that feel completely alien compared with modern Minecraft.

Modern Minecraft:

```text
Nether
End
Enchanting
Villages
Redstone
Bosses
Thousands of blocks/items
```

Ancient Minecraft:

```text
blocks
human-looking thing walking around
???
```

Trying to "beat" those versions is like trying to finish the calculator app.

There isn't really an ending.

You simply exist.

---

# 🪣 Important Minecraft Knowledge

At some point:

> "How to make a bucket?"

This could have been a real-world question.

It was not.

The correct context was:

# Minecraft.

Three iron ingots.

Problem solved.

---

# 🧠 My Development Process

My development process can generally be represented as:

```text
1. Have idea
2. Idea seems easy
3. Start coding
4. Discover idea is not easy
5. Fix bug
6. New bug
7. Fix new bug
8. Original bug returns
9. Ask why computers exist
10. Fix one character
11. Everything works
12. Do not touch anything
13. Touch something
14. Everything breaks
15. Repeat
```

---

# 🐛 Bug Classification System

### Level 1

```text
I forgot a semicolon.
```

Fine.

### Level 2

```text
Variable name typo.
```

Annoying.

### Level 3

```text
The JavaScript console is red.
```

Concerning.

### Level 4

```text
The WebAssembly worker has stopped communicating.
```

Bad.

### Level 5

```text
THE BOARD SQUARES HAVE CHANGED SHAPE.
```

Catastrophic.

### Level 6

```text
It started working and I don't know why.
```

**DO NOT TOUCH IT.**

---

# 🖥️ Localhost

Another important programming milestone:

```text
python -m http.server
```

Suddenly your folder is a website.

Until you click the wrong thing and discover:

```text
Directory listing for /
```

and wonder why your beautiful website has transformed into an Apache server from 2003.

Usually:

```text
index.html
```

is the answer.

`index.html` has saved many lives.

---

# 🧩 WebAssembly

At some point I asked:

> What is a `.wasm` file?

And then later actually needed one for Stockfish.

That's basically programming progression:

```text
Stage 1:
"What is this weird file?"

Stage 2:
"I need this weird file."

Stage 3:
"WHY IS THIS WEIRD FILE NOT LOADING?"

Stage 4:
"Oh, it's working."

Stage 5:
"Never touch it again."
```

---

# 🤖 AI

I like experimenting with AI and seeing what it can build, explain, debug, or completely misunderstand.

A recurring part of the experience is:

```text
Lucas:
Can you change this ONE thing and leave everything else alone?

AI:
Absolutely.

*changes seventeen unrelated things*
```

This is why version control exists.

---

# 🧠 AI IQ

At some point the extremely scientific question arose:

> What is ChatGPT's IQ?

Which eventually resulted in the completely legitimate measurement:

```text
2147483647
```

Coincidentally also:

```text
INT_MAX
```

Clearly this is peer-reviewed research.

---

# 🍓 Strawberry Research Institute

An important AI benchmark:

> How many strawberries are there in the word `r`?

This is obviously nonsense.

Which is exactly why it is important.

The broader tradition of asking AIs weird spelling/counting questions exists because watching a giant neural network lose a fight against a tiny word is objectively funny.

---

# 🔤 Language

I am bilingual, so sometimes I know exactly what something means but only remember the word in one language.

This produces sentences such as:

```text
what is 暴露 in english
```

or:

```text
这个东西英文叫什么
```

followed immediately by another paragraph in English.

My keyboard has accepted its fate.

---

# ⌨️ Keyboard Smash

Sometimes language itself becomes insufficient.

Then we enter:

```text
ddipdhfelv fphkegvjwe dfoesjgbidk
```

Is this:

- English?
- Chinese?
- Encryption?
- A new programming language?
- Keyboard violence?

Nobody knows.

Sometimes the correct linguistic classification is simply:

# keyboard smash

---

# 👋 The Great Hello Decomposition

At some point a conversation went approximately:

```text
hello chatgpt
bye chatgpt
hello chatgpt
bye chatgpt
hello chatgpt
bye chagpt
ello chagpt
ye cagpt
llo cgpt
ee gpt
lo gt
e g
t
```

Eventually communication reached:

```text
‎
```

At which point we had successfully compressed ChatGPT into whitespace.

This may be the world's least useful compression algorithm.

---

# 🗣️ ChatGPT Naming Department

ChatGPT has accumulated several names.

Including variations approximately like:

```text
ChatGPT
chatgpt
chatgot
chagpt
cagpt
cgpt
gpt
gt
g
```

At this rate the final version will simply be:

```text
.
```

---

# 🧑‍💻 Coding Philosophy

Here is a highly accurate program describing development:

```cpp
#include <iostream>
using namespace std;

int main()
{
    bool works = false;
    int attempts = 0;

    while (!works)
    {
        attempts++;

        cout << "Attempt " << attempts << ": ";
        cout << "WHY DOESN'T THIS WORK" << endl;

        if (attempts == 47)
        {
            works = true;
        }
    }

    cout << "WAIT WHY DOES IT WORK NOW" << endl;
    return 0;
}
```

The most dangerous sentence in programming is:

> **"I'll just change one tiny thing."**

---

# 📊 Completely Scientific Lucas Statistics

```text
Curiosity             ████████████████████ 100%
Programming           ███████████████████░  95%
Chess                  ██████████████████░░  90%
Random experiments     ████████████████████ 100%
GitHub                 █████████████████░░░  85%
Debugging              ████████████████████ 100%
Creating new bugs      ████████████████████ 100%
Keyboard accuracy      ███████████░░░░░░░░░  ???%
Giving up              ██░░░░░░░░░░░░░░░░░  10%
Coming back anyway     ████████████████████ 100%
```

These statistics have not been reviewed by any reputable scientific organization.

---

# 🎮 Things I Like Making

My repositories may contain:

```text
Chess
Checkers
Browser games
AI experiments
Websites
Utilities
Algorithms
Programming-language experiments
GitHub Pages
Random prototypes
Things with no reasonable category
```

The unifying design philosophy is:

> If it's interesting, try building it.

---

# 🏗️ Project Development Lifecycle

### Phase 1 — Inspiration

```text
WAIT I HAVE AN IDEA
```

### Phase 2 — Confidence

```text
this should be easy
```

### Phase 3 — Reality

```text
why
```

### Phase 4 — Debugging

```text
WHY
```

### Phase 5 — Despair

```text
AHHHHHHHHHHHHHHHHHHHHHHHHHHHHHHH
```

### Phase 6 — Discovery

```text
oh
```

### Phase 7 — Success

```text
YOOOOOOOOOOOO
```

### Phase 8 — Feature Creep

```text
wait can we also add...
```

### Phase 9

Return to Phase 3.

---

# 🏆 Achievement Cabinet

Current known GitHub achievement adventures:

## 🏆 YOLO

Unlocked basically by accident.

```text
Wanted achievement
↓
Didn't get achievement
↓
Stopped caring
↓
Achievement
```

Excellent system.

## 🤠 Quickdraw

Unlocked intentionally.

```text
Create PR
↓
Close PR extremely quickly
↓
Gitty up!
```

The achievement description literally confirms:

> Closed within 5 minutes of opening.

Mission accomplished.

## 🦈 Pull Shark

Target / waiting room.

```text
Merge PR
Merge another PR
↓
WHERE SHARK
```

---

# 🌟 Future GitHub Bosses

Potential future targets:

```text
🦈 Pull Shark
👯 Pair Extraordinaire
🧠 Galaxy Brain
⭐ Starstruck
```

Starstruck is especially funny because unlike Quickdraw, you cannot simply press buttons very quickly.

You need other humans.

This significantly increases the difficulty.

---

# 🪪 Main vs Alt

If you're reading this on:

```text
LucasLiNotFound4747
```

yes, this is an alternate account.

And yes:

```text
LucasLiNotFound4747
```

is objectively a username that sounds like GitHub attempted an HTTP request for Lucas and received:

```text
404 LUCAS NOT FOUND
```

Possible API response:

```json
{
  "status": 404,
  "error": "LucasLiNotFound4747",
  "message": "Lucas was here approximately five seconds ago."
}
```

---

# ❓ FAQ

## Are you actually called Lucas?

Yes.

Unless the server returns 404.

---

## What's your favorite programming language?

C++.

---

## Why C++?

Because apparently I enjoy having both:

```text
extreme control
```

and:

```text
extreme opportunities to ruin everything
```

---

## Do you make websites?

Yes.

---

## Do you make games?

Yes.

---

## Do you play chess?

Yes.

---

## Have you modified chess until it barely resembles chess?

Also yes.

---

## Why?

Excellent question.

---

## Do your projects always work?

Define **work**.

---

## Do you use GitHub Pages?

Yep.

---

## Do you know Git?

Increasingly.

---

## Do you know what a contributor is now?

YES.

This required an entire educational arc.

---

## Can a contributor destroy `main`?

Not just because they're a contributor.

Thank goodness.

---

## What's a collaborator?

Someone you've actually granted repository access to.

---

## What's a fork?

Your own connected copy of somebody else's repository.

---

## What's a star?

GitHub bookmark + appreciation button.

---

## What's `.gitignore`?

The file where you tell Git:

> Please stop looking at this garbage.

---

## Does the `.gitignore` template `AL` mean "all"?

NO.

We have established this.

---

# 🧪 Current Research Topics

Important unresolved questions include:

```text
How many programming languages can I mess with?

How many GitHub achievements can I accidentally unlock?

How many chess variants can exist before chess stops being chess?

How many times can a website break before it becomes performance art?

Why does code sometimes work after changing nothing?

Why is naming variables harder than writing algorithms?

Why did refreshing fix it?

Why did refreshing break it?

Why?
```

Research continues.

---

# 📜 The Programmer's Prayer

```text
Please compile.
Please compile.
Please compile.
Please compile.

...

IT COMPILED.

Please run.
Please run.
Please run.
Please run.

...

IT RAN.

Please give correct output.

...

Wrong Answer.
```

---

# 🧯 Emergency Debugging Procedure

If something breaks:

```text
Step 1: Read error.
Step 2: Ignore error.
Step 3: Stare at code.
Step 4: Change something unrelated.
Step 5: Undo it.
Step 6: Refresh.
Step 7: Somehow fixed.
Step 8: Pretend this was intentional.
```

For severe incidents:

```text
git reset
```

For extremely severe incidents:

```text
AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA
```

---

# 💬 Typical Conversation During a Project

```text
Lucas:
can we add this

ChatGPT:
yes

Lucas:
bruh this broke the other thing

ChatGPT:
found it

Lucas:
okay fix it

ChatGPT:
fixed

Lucas:
YOOOO

Lucas, 13 seconds later:
wait can we also add...
```

And thus the software development cycle continues forever.

---

# 🧠 Things Programming Has Taught Me

Programming teaches you that:

1. Computers are extremely fast.
2. Computers are extremely literal.
3. Computers will execute exactly what you wrote.
4. Unfortunately, what you wrote is not what you meant.
5. A one-character mistake can destroy everything.
6. A one-character fix can restore everything.
7. `index.html` is more powerful than it looks.
8. Never trust a file path.
9. Never trust yourself after saying "this will only take five minutes."
10. Version control is not optional once your projects become sufficiently chaotic.

---

# 🔥 The Most Important Rule

If the project currently works:

```text
DO NOT RANDOMLY REWRITE EVERYTHING.
```

Make one change.

Test it.

Commit it.

Then make the next change.

This lesson may or may not have been learned through experience.

---

# 📦 Repository Quality Scale

My repositories can be classified into approximately five categories:

### 🟢 Level 1 — Actually Useful

Someone could legitimately use this.

### 🔵 Level 2 — Experiment

Built to learn something.

### 🟡 Level 3 — Weird but Functional

Nobody asked for this.

It works anyway.

### 🟠 Level 4 — Why Did I Make This?

No explanation available.

### 🔴 Level 5 — Lucas Engineering

```text
IT WORKS
DO NOT ASK HOW
DO NOT MODIFY LINE 173
DO NOT REFRESH TWICE
```

---

# 🌌 Final Words

I like programming because you can start with absolutely nothing except an idea and eventually turn it into something that actually runs.

Sometimes that thing is useful.

Sometimes it's a game.

Sometimes it's a website.

Sometimes it's an AI experiment.

Sometimes it's a programming language with commands like:

```text
FRGETABTIT
```

Sometimes it's chess except physics has been introduced.

And sometimes the entire accomplishment of the day is:

```text
the squares are finally squares
```

But that's kind of the fun of it.

There's always another thing to learn, another bug to fix, another language to investigate, another ridiculous project idea, and another opportunity to ask:

> **"Wait... is this actually possible?"**

And then immediately attempt it.

---

# 👋 Thanks for visiting!

If you're browsing my repositories:

**Welcome.**

Some projects are serious.

Some are experiments.

Some are jokes.

Some started as jokes and became serious projects.

Some started as serious projects and became jokes.

And somewhere in here, there is probably a bug.

```cpp
if (youFoundBug)
{
    cout << "feature" << endl;
}
```

### See you around GitHub. 🚀

---

<sub>
README status: probably longer than necessary.<br>
Lucas status: probably building something.<br>
Bug status: definitely alive somewhere.<br>
HTTP status: 4747 Lucas Not Found.
</sub>
