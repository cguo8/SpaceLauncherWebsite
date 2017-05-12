<section id="example">
  <h2>e.g.</h2>
  <ul>
    <li>Launch an app, open a website, or run a script.</li>
    <ul>
      <li>Spacebar S -> launch Safari</li>
      <li>Spacebar N -> launch Notes</li>
      <li>Spacebar G -> open a website</li>
    </ul>
    <li>Simulate a keystroke (with/without modifiers)</li>
    <ul>
      <li>Spacebar Q -> simulate F11</li>
      <li>Spacebar X -> simulate Control-Option-Shift-Command-A</li>
    </ul>
    <li>More keys, more actions</li>
    <ul>
      <li>Spacebar F then D -> open Documents folder</li>
      <li>Spacebar F then W -> open Downloads folder</li>
      <li>Spacebar A W E S O M E -> launch your AppleScript to say "you are awesome"</li>
    </ul>
  </ul>
</section>
<section id="actions">
  <div class="action_button">
    <a id="download" class="pure-button pure-button-primary" href="/download/SpaceLauncher.zip" download>Download Trial</a>
    <p id="action_comment">Requires macOS 10.10 or later</p>
  </div>
  <div class="action_button">
    <a id="purchase" class="pure-button pure-button-primary" href="https://spacelauncherapp.onfastspring.com/spacelauncher">Buy Now</a>
    <p id="action_comment">Buy SpaceLauncher for $14.99</p>
  </div>
</section>
<section>
  <h2>Why spacebar?</h2>
  <p>It's bigger.</p>
</section>
<section>
  <h2>How to type space?</h2>
  <p>Just type spacebar.</p>
  <p>SpaceLauncher is smart to recognize it.</p>
</section>
<section>
  <h2>Setup</h2>
  <img src="{{ '/img/preferences-screenshot.png?v=' | append: site.github.build_revision | relative_url }}" alt="preferences screenshot" data-action="zoom">
</section>
<section>
  <h2>I can't memorize these</h2>
  <p>Don't memorize. Just practice. Your fingers can memorize them easily.</p>
  <p>And, SpaceLauncher will show you a hint,</p>
  <img src="img/hint-window-screenshot.png" alt="hint window screenshot" data-action="zoom">
  <p>depending on your typed keys after pressing spacebar down.</p>
  <img src="img/hint-window-with-typed-keys-screenshot.png" alt="hint window screenshot" data-action="zoom">
  <p>Moreover, only rarely used actions are highlighted (the keys used recently are gray), so you can find out the action you actually need quickly.</p>
  <img src="img/hint-window-with-some-gray-rows-screenshot.png" alt="hint window with some gray rows" data-action="zoom">
</section>
<section>
  <h2>But, it is not suited to everybody.</h2>
  <p>It depends on your way of typing keys. So ...</p>
</section>
<section id="try">
  <h2>Stop reading, try it.</h2>
  <p>Feel safe to download. The app is signed, and it will not connect the Internet without your permission.</p>
  <div class="action_button">
    <a id="download" class="pure-button pure-button-primary" href="/download/SpaceLauncher.zip" download>Download Trial</a>
    <p id="action_comment">Requires macOS 10.10 or later</p>
  </div>
</section>
<section id="faq">
  <h2>Questions and Answers</h2>
  <ul>

    <li class="accordion">How to type a lot of spaces continuously?</li>
    <div class="panel">
      <p>It's uncommon,<br>
      but if you really need it, hold shift and spacebar.</p>
    </div>

    <li class="accordion">What does the option "After space key down, ignore keys within 0.2 seconds" mean? Why do I need it?</li>
    <div class="panel">
      <p>If you often trigger SpaceLauncher actions when inputting text, that is because you type fast so that the letter after space go before releasing spacebar. This option gives a delay. After you pressing spacebar, SpaceLauncher waits for a delay, then start to recognize keys for actions.</p>
    </div>

    <li class="accordion">What's wrong with the hint window? Some rows are gray.</li>
    <div class="panel">
      <p>This is intended. The keys used recently will be gray. The keys never used or used several weeks ago will be white or less white depending on your last usage.</p>
      <p>I also considered reordering the rows in hint window to show less used rows first. But I noticed if I referred to a row several times, I would expect it to appear in the same place. Reordering made me difficult to locate it.</p>
    </div>

    <li class="accordion">Can I change the hint window's location and size?</li>
    <div class="panel">
      <p>Yes, you can. Holding spacebar until the hint window appears, then you drag the title bar to move the window, or drag the edge to resize width (height will be changed automatically depending on contents).</p>
    </div>

    <li class="accordion">Can I change the hint window's appearance or theme?</li>
    <div class="panel">
      <p>No, you can not, at least not now.</p>
      <p>I lack confidence in user interface design, so I just chose the native <a target="_blank" href="https://developer.apple.com/library/content/documentation/UserExperience/Conceptual/OSXHIGuidelines/WindowPanels.html">Translucent Panels</a>. If you think the hint window is really ugly, let me know.</p>
    </div>

    <li class="accordion">Are you going to add new features?</li>
    <div class="panel">
      <p>Yes.</p>
      <p>There are lots of features I wanted to add when I make SpaceLauncher. I had to stop myself to add new features before release. e.g.</p>
      <ul>
        <li>Support more actions</li>
        <li>Support app-specific actions</li>
        <li>Show current hotkeys in menu bar extras.</li>
        <li>Easy to input dozens of spaces</li>
        <li>Easy to add new/delete actions</li>
        <li>Generate actions for a folder / all applications</li>
        <li>...</li>
      </ul>
      <p>Thanks to AppleScript, most of these can be implemented via AppleScript. But making them native in SpaceLauncher will be more user-friendly. Before that, you can try AppleScript for your customization.</p>
      <p>Let me know what you have done with AppleScript or what you are going to do with AppleScript if I can help. And don't forget, tell me the new feature you want. You make SpaceLauncher better!</p>
    </div>

    <li class="accordion">How to launch an AppleScript to say "you are awesome"</li>
    <div class="panel">
      <p>In Script Editor, type <code>say "you are awesome"</code>, save as Application.<br>In SpaceLauncher, add an action to open URL, choose the AppleScript file.</p>
    </div>

  </ul>
</section>