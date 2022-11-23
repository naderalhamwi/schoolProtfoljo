---
Title: SCSS
Description: This is our index page.
Template: technologies
---

<div class="tech-main">
    <div class="tech-nav">
        <ul>
            <li><a href="python">PTHON</a></li>
            <li><a href="html">HTML</a></li>
            <li><a href="javascript">JAVASCRIPT</a></li>
            <li><a href="css">CSS</a></li>
            <li><a href="scss">SCSS</a></li>
            <li><a href="php">PHP</a></li>
            <li><a href="sqlite">SQLITE</a></li>
            <li><a href="git">GIT</a></li>
        </ul>
    </div>
    <div>
        <p>
        Sass (short for syntactically awesome style sheets) is a preprocessor scripting language that is interpreted or compiled into Cascading Style Sheets (CSS). SassScript is the scripting language itself.
        Sass consists of two syntaxes. The original syntax, called "the indented syntax," uses a syntax similar to Haml. It uses indentation to separate code blocks and newline characters to separate rules. The newer syntax, SCSS (Sassy CSS), uses block formatting like that of CSS. It uses braces to denote code blocks and semicolons to separate rules within a block. The indented syntax and SCSS files are traditionally given the extensions .sass and .scss, respectively. 
        </p>
        <textarea disabled>
        Example:

        $primary-color: #3bbfce;
        $margin: 16px;

        .content-navigation {
        border-color: $primary-color;
        color: darken($primary-color, 10%);
        }

        .border {
        padding: $margin / 2;
        margin: $margin / 2;
        border-color: $primary-color;
        }
        </textarea>
    </div>
</div>