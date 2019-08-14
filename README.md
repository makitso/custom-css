# common.css

<h3>
<a id="user-content-features" class="anchor" aria-hidden="true" href="#features">
<svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true">
<path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z">
</path>
</svg>
</a>Features
</h3>

<p>The common.css file contains style changes for all webtrees standard themes.</p> 
<p>The goal of these changes is to utilize screen space a bit better and also provide better mobile support.</p>

Style changes are for webtrees 2.0 only. for all themes for github as of 14 August 2019
</p>

<h3>
<a id="user-content-installation" class="anchor" aria-hidden="true" href="#installation">
<svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true">
<path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z">
</path>
</svg>
</a>Installation
</h3>

<p>The common.css file contains style changes for standard webtrees themes.  

Style changes to webtrees 2.0 for all themes for github as of 14 August 2019
</p>
<p>
There are two ways to use these style changes for webtrees.

<ul>
<li>Option 1 - If you only want these changes to apply to one theme then copy the "contents" of the 
	   common.css to the end of the specific style sheet, located in /public/css. </li>

<li>Option 2 - Use the styles in common.css in all standard webtrees themes - Note only will work for 2.0 github updates as of 12 March 2019.
 
           There are several steps necessary in order to use a common.css file in the 2.0 version of webtrees.
           <ul>
           <li>Step 1 - copy this style sheet into folder /public/css </li>
           <li>Step 2 - Go to Control panel / All Modules and enable module CSS and JSS and then do a save </li>
	   <li>Step 3 - Go to Control panel / All Modules and select the wrench [Preferences] for CSS and JSS  </li>
	   <li>Step 4 - Add this value in the <head> element   <link rel="stylesheet" href="public/css/common.css">  </li>
			</ul>
</ul>
</p>

<h3><a id="user-content-license" class="anchor" aria-hidden="true" href="#license">
	<svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>License</h3>
<ul>
<li>Copyright (C) 2019 webtrees development test team</li>
</ul>
<p>This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.</p>
<p>This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.</p>
<p>You should have received a copy of the GNU General Public License
along with this program. If not, see <a href="http://www.gnu.org/licenses/" rel="nofollow">http://www.gnu.org/licenses/</a>.</p>
