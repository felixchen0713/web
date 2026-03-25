---
title: "Page"
draft: false
---

<h2>Notes</h2>

<p>You can write anything here.</p>

<textarea id="notes_box" placeholder="Write something..." style="width:100%; height:140px; padding:10px; font-size:16px;"></textarea>

<br><br>

<button onclick="saveNotes()" style="padding:8px 16px; font-size:16px;">Save</button>

<script>
function saveNotes() {
  const value = document.getElementById("notes_box").value;
  console.log("NOTES_CAPTURE:", value);

  const out = document.createElement("pre");
  out.textContent = "Saved:\n" + value;
  document.body.appendChild(out);
}
</script>