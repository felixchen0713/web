---
title: "Session Notes"
draft: false
---

<h2>Session Notes</h2>

<p>
You can continue writing your notes here.
</p>

<label>Notes</label>

<textarea id="notes_box" placeholder="Continue writing..." style="width:100%; height:160px; padding:10px; font-size:16px;"></textarea>

<br><br>

<button onclick="saveNotes()" style="padding:8px 16px; font-size:16px;">Save</button>

<script>
function saveNotes() {
  const value = document.getElementById("notes_box").value;
  console.log("CAPTURE:", value);

  const out = document.createElement("pre");
  out.textContent = "Saved:\n" + value;
  document.body.appendChild(out);
}
</script>