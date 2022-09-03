# RoutineHub Archive
A static archive of RoutineHub.
<div><form>
 <input required type="url" pattern="https?:\/\/(www\/.)?routinehub\.co\/shortcut\/\d+\/?" placeholder="https://routinehub.co/shortcut/69/" id="shortcutUrl"> <input type="submit" value="Load Archived Page">
</form> <script>document.forms[0].onsubmit=e=>{e.preventDefault();let rhid = shortcutUrl.value.match(/routinehub\.co\/shortcut\/(\d+)/)[1];if(!rhid){alert("That doesn't look like a RoutineHub URL. Only routinehub.co/shortcut/ URLs are supported at the moment.")}else{location.href="shortcut.html?"+rhid}}</script></div>

## Limitations
 - Shortcuts marked NSFW were not saved
 - Only the latest version of each shortcut is saved
