# Как мне начать кодить? (Я не знаю, как программировать).
Ниже есть несколько полезных ссылок для изучения программирования. Если вы что-то не понимаете, не стесняйтесь задавать вопросы в канале `#разработка` на нашем [дискорд сервере](https://discord.gg/ss14). Если нвы не можете найти то, что ищите, попробуйте поискать "Как сделать X в C#". Скорее всего вы найдёте несколько примеров.

Если у вас уе есть опыть (читать как: Понимаете такие вещи как "классы" и "поток выполнения") и хотели бы научиться на практике, попробуйте посмотреть баг репорты, помеченные как [лёгкие для новичков](https://github.com/space-wizards/space-station-14/labels/Beginner%20Friendly) в репозитории гитхаба. Обычно они достаточно простые и вам всегда смогут помочь с решением в дискорде.

Так же вы, возможно, пришли сюда, желая добавить новые предметы в игру. Это возможно даже не изучая программирование, однако вы будете достаточно ограничены в том, что вы сможете сделать. Но вам всё равно придётся изучить гит для этого (читать далее)!

Если вы хотите сделать что-нибудь более сложнее, мы рекомендуем вам прочитать всё в разделе [**Для начала**](./setting-up-a-development-environment.md) и потом прочитать **SS14 на примере**, где рассказывается про основы работы с игрой.

## Гайды

### C#
Это язык программирования, который вы будете использовать для разработки SS14. Если вы раньше не программировали до этого, C# станет для вас хорошим началом!

**TODO BEGIN: add russian resources here**

**[C# A Player's Guide 5th Edition](https://www.amazon.com/dp/0985580151)**
A very engaging book for beginners to C#. Very modern, making use of C#10 and .NET 6 with tons of projects and challenges to actually make use of your coding skills. Highly recommended. Buy whatever the newest edition is (regardless of what this says), as we always stay up to date.

**[CSharp Fundamentals for Absolute Beginners | Channel 9](https://channel9.msdn.com/Series/CSharp-Fundamentals-for-Absolute-Beginners)**
A video series covering the absolute basics of programming, C# style. Also walks you through installing an IDE (a program that makes it much easier for you to write code).

**[Знакомство с C# | Microsoft](https://learn.microsoft.com/ru-ru/dotnet/csharp/tour-of-csharp/tutorials/)**
Видео там не очень (быстро пробегаются по таким терминам, как "переменная", "строка" и "интерполяция"), но сами гайды отличны. Если вы предпочитаете интерактивные гайды вместо просмотра видео, можете открыть их в браузере [тут](https://docs.microsoft.com/en-us/dotnet/csharp/tour-of-csharp/tutorials/hello-world).

**Разные ресурсы по C# от Microsoft**
Для тех, кто уже имеет некоторый опыт (читать как: знает, что такое "современный, объектно-ориентированный и безопасный язык программирования", т.к. это первая строка), [документация по C#](https://docs.microsoft.com/ru-ru/dotnet/csharp/getting-started/) предоставляет несколько примеров, как использовать C# и показывает как использовать Visual Studio для написания кода на C#. [Основные понятия программирования](https://docs.microsoft.com/ru-ru/dotnet/csharp/programming-guide/) предоставляют более специфичные примеры особенностей языка.

**[Learn C# in Y minutes](https://learnxinyminutes.com/docs/csharp/)**
Reference sheet presented through a massive C# file. Again, this is more useful for those who already understand how to program and just need a quick reference for what the syntax is. 

**TODO END**

### Git
Git является "программой для контроля версий", т.е. то, что позволяет нескольким разработчикам работать над одним проектом и не превращать рабочий процесс в хаос. Сначала git может показаться непонятной пугающей бессмыслицей, но потом, когда у вас "щёлкнет в голове", вы так же станете убеждать людей в том, что "на самом деле, это не так сложно. Просто представь ветку..."

**[Git для разработчиков SS14](./git-for-the-ss14-developer.md)**
Гайд хорош сам по себе и имеет много отличных ресурсов для изучения git. Там объясняется, например, его роль в разработке SS14.

**[Learn Git Branching](https://learngitbranching.js.org/?locale=ru_RU)**
Замечательный гайд на Git в виде игры. Отлично сочетается с "Git для разработчиков SS14", так что вы сможете понять его на более глубоком уровне.

### Другое

**TODO: Add here resources for learning programming in russian**

**[CS50 | Harvard](https://cs50.harvard.edu/college/2021/spring/weeks/6/)**
Teaches computer programming and how computers work. Covers a broad swathe of topics (different languages like C and Python, algorithms, memory, etc). To oversimplify: learning things like "for loops" and "if statements" teaches you how to talk the talk. Breaking down why algorithms work, the differences between programming languages, actually writing programs to solve puzzles, etc. is the "walk the walk" part. You can get started without this and pick it up naturally over time, though it's a slower process.
