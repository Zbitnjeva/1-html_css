- [GeekBrains. HTML/CSS. Interactive course.](#geekbrains-htmlcss-interactive-course)
  - [Lesson 1. Basic concepts in web development](#lesson-1-basic-concepts-in-web-development)
  - [Lesson 2. HTML5 Basics](#lesson-2-html5-basics)
  - [Lesson 3. Basic CSS](#lesson-3-basic-css)
  - [Lesson 4. Pseudo-classes, Table Layout](#lesson-4-pseudo-classes-table-layout)
  - [Урок 5. Основы позиционирования, работа с Flexbox](#урок-5-основы-позиционирования-работа-с-flexbox)
# GeekBrains. HTML/CSS. Interactive course.
***
## Lesson 1. Basic concepts in web development
  1.  Create home page of your site
  2.  Configure code editor
  3.  Enable autosaving files
  4.  Change font size to convenient for you
  5.  Enable autoformat code when saving
  6.  Add html document structure (For all subsequent pages you will also need to add html document structure when creating)
  7.  Create a header with any text, no more than 3 words(h1)
  8.  Create a paragraph with any text
  9.  Create a header less than the previous level (h3), add no more than 3 words
  10. Create a header (h4), add no more than 5 words.
  11. Add a paragraph with any text not exceeding 15 words
  12. Create header (h3) add no more than 3 words
  13. Add a paragraph with any text not exceeding 10 words
  14. Create a header (h3), add no more than 3 words
  15. Add a paragraph with any text not exceeding 10 words
  16. Add dividing line (hr)
  17. Create a paragraph with the text "All rights reserved"
## Lesson 2. HTML5 Basics
1. Site hat (on each page):
   - Site menu:
     - Main.
     - Contacts.
2. All contents of the home page from PP 1.
3. After hr element (from the first LV), add a contact list containing 3 elements
list.
   - any text not more than 5 words
   - telephone number;
   - email address.
4. Create «Contacts» page. Use English only when creating folders and pages
letters.
5. Page «Contacts»:
   - web site hat;
   - header Contact Us (h2);
   - paragraph with any text: no more than 10 characters;
   - any image (not more than 350px);
   - Address header (h4);
   - paragraph with any text: no more than 7 characters;
   - with the title Phone (h4);
   - list of 2 phone numbers;
   - the title of Online service (h4);
   - list of 2 links to the site and mail:
   - Send us message header (h4);
   - Full Name text and text input field;
   - Email text and mail input field;
   - Message text and textarea element;
   - Send button with submit text;
   - interactive Google Map;
6. Site Footer: copy from the home page, do not need to re-create elements. Below is listed what you need to copy.
   1. Title (h3): no more than 3 words.
   2. Paragraph with any text: no more than 10 words.
   3. Dividing line (hr).
   4. Contact list.
    - any text - not more than 5 words;
    - telephone number;
    - email address.
   5.   Paragraph with the text «All rights reserved».
## Lesson 3. Basic CSS
1. Create a stylesheet and connect to each page.
2. Set the font type for the entire site:
   - font-family: sans-serif.
3. Assign class and style for all paragraphs
   - font-size: 16px;
   - line-height: 26px;
   - color: #1F3F68.
4. Create a class and assign styles for h1 header:
   - font-size: 64px;
   - color: #1F3F68.
5. For the h2 header (on the contacts page) create a class and assign styles:
   - font-weight: 500;
   - font-size: 44px;
   - text-align: center.
6. Header h3 create class and set styles:
   - font-size: 36px;
   - text-align: center.
7. Headers h4 create class and set styles
   - font-size: 20px;
   - line-height: 30px;
   - color: #1F3F68.
8. For all input fields (input, textarea) specify the common class and its styles:
   - border: 1px solid #356EAD;
   - box-sizing: border-box;
   - border-radius: 10px;
   - opacity: 0.4.
9. The Send Form button assign a class and style to it:
   - background: #5A98D0;
   - box-shadow: 5px 20px 50px rgba(16, 112, 177, 0.2);
   - border-radius: 10px;
   - font-weight: 500.
   - font-size: 16px;
   - line-height: 26px;
   - text-align: center;
   - color: #FFFFFF;
   - text-transform: uppercase.
## Lesson 4. Pseudo-classes, Table Layout
1. Provides a site image ([simple picture](https://ww.figma.com/proto/4DoJjp5UQzCQJcoGXblW/html-css-Copy?nodeid-=1%3A966&ing=zoomin-m)). It’s got different colors
the blocks to which you want to divide the page. You do not need to make a layout, just add the elements div c class, which are highlighted in the image.
2. You need to add all the contents of 3 homework to the blocks marked in the site image.
3. There is no need to add any new elements from the layout. You will start working with it in lesson 6.
4. All blocks are given a logical class name. It is forbidden to use an enumeration (block1, block2, block3...block378).
5. (*) For the «Contacts» page there is also a page image, but without partitioning into blocks. 
   [Here](https://www.figma.com/proto/4DoJjp5UQzCQkJcoGXblW/html%2Fcss-(Copy)?node-id=1%3A811&scaling=-zoom) is required to independently divide the site into blocks.
## Урок 5. Основы позиционирования, работа с Flexbox
1. В файле стилей первой строчкой добавить обнуление стилей * {margin: 0; padding: 0;}.
2. В файле стилей создать блок container, отвечающий за центрирование нашей страницы:
.container { width: 1140px; margin: 0 auto; }
3. В шапке сайта необходимо расположить элементы горизонтально, текст «Главная» должен
располагаться слева, «Контакты» — справа.
4. Заголовку h1 указать ширину 510px.
5. Тексту под заголовком h1 указать ширину 425px.
6. В HTML-файле class="what-we-do" добавить класс container, чтобы получилось
class="what-we-do container" для центрирования содержимого блока what-we-do:
   -  Блоку карточки (заголовок h4: Make your business, смотри макет ниже и p) указать
   значение ширины 359px.
   -  Создать ещё 2 карточки товара, как представлено в [изображении макета](https://www.figma.com/proto/4DoJjp5UUQzCQkJcoGXblW/html%2Fcss-(Copy)?node-id=1%3A966&scaling=min-zoom). Итого
   получится 3 карточки.
   - Расположить их горизонтально и выставить равные отступы между ними.
7. В подвале сайта:
   - Добавить центрирование всего контента, в подвале сайта внутри блока footer
   создать блок container для центрирования содержимого. Должна получиться
   структура:
      ```
      <div class="footer">
      <div class="container">Содержимое футера</div>
      </div>
      ```
   -  Блоку контента (h3 "Intersted to woek") в верхней части футера указать ширину 340px.
   - Тексту (p) в подвале сайта указать ширину 495px.
   -  Список в нижней части подвала (номер телефона и email) расположить горизонтально
и выставить равные отступы между ними.
8. Страница «Контакты»:
- Добавить центрирование всей контентной части страницы с помощью блока
container.
- В соответствии с изображением страницы «Контакты» разместить слева блок с
контактами, справа — блок формы заполнения данных.
- Карту сайта сделать на всю ширину container.