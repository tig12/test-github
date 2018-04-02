{::nomarkdown}

This repository is used to learn using github.
<br>
<br>My first question is : how-to avoid using github markdown syntax in README and similar files ?
<br>Markdown is great but is not standardized, so the risk is to use github-specific syntax. This is a risk because it reduces documentation portability : I don't want to be stuck with github and have the ability to also publish code in alternative systems, such as gitlab or gitea, and still have my README files displayed correctly.
<br>
<br>At first sight, I see two alternatives : 
<ul>
    <li>Use a subset of markdown common to different publication softwares.</li>
    <li>Use html</li>
</ul>

The rest of this README contains tests to see how html is renderd by github.

<ul>
    <li>
        <a href="#par1">Testing html in README.md</a>
        <ul>
            <li><a href="#tables">What about tables ?</a></li>
        </ul>
    </li>                                                                                             
    <li>
        <a href="#par2">Paragraph2</a>
    </li>
    <li>
        <a href="#sum-det">summary details tags</a>
    </li>
</ul>

<h1><a name="par1">Testing html in README.md</a></h1>
The list of html tags allowed by github can be found here : <a href="https://github.com/jch/html-pipeline/blob/master/lib/html/pipeline/sanitization_filter.rb#L41-L44">https://github.com/jch/html-pipeline/blob/master/lib/html/pipeline/sanitization_filter.rb#L41-L44</a>
<br>
<br><code>h1 h2 h3 h4 h5 h6 h7 h8 br b i strong em a pre code img tt div ins del sup sub p ol ul table thead tbody tfoot blockquote dl dt dd kbd q samp var hr ruby rt rp li tr td th s strike summary details</code>

<pre>
Here is a piece of code 

in pre tag
</pre>

and <code>some code in code tag</code>
<br>
<br>Observe newlines, &lt;br> tags,
<br>And a simple br ?
<div style="color:orange; background:blue; padding:2em;">and div tags with css</div>

<h2><a name="tables">What about tables ?</a></h2>
<table>
    <tr><th>col 1</th><th>col2</th></tr>
    <tr>
        <td>cell 1 1</td>
        <td>cell 1 2</td>
    </tr>
    <tr>
        <td>cell 2 1</td>
        <td>cell 2 2</td>
    </tr>
</table>

<h1><a name="par2">Paragraph2</a></h1>
And an image :
<br><img src="https://www.gnu.org/graphics/heckert_gnu.transp.small.png" alt="a test of image" />

<h1><a name="sum-det">summary details tags</a></h1>
summary details

 <details>
  <summary>Summary test</summary>
  <p>A first p</p>
  <p>A second p</p>
</details> 


{:/}