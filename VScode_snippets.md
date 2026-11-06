{
  "Main Body Structure": {
    "prefix": "titleBody",
    "body": [
      "<<nobr>>",
      "\t<video id=\"bg-video\" autoplay loop muted playsinline>",
      "\t\t<source src=\"sources/Assets/${1:video_name}.mp4\" type=\"video/${2:mp4}\">",
      "\t</video>",
      "\t<<audio \"${3:audio_id}\" play loop>>",
      "\t<div class=\"titleParent\">",
      "\t\t<<type 60ms >><p class=\"titleTop\">${4:Title Top}</p><</type>>",
      "\t\t<<type 50ms >><p class=\"titleBottom\">${5:Title Bottom}</p><</type>>",
      "\t</div>",
      "\t<div class=\"buttonsParent\">",
      "\t\t<div class=\"button\">",
      "\t\t\t[[${6:Button Text}->${7:Target Passages}]]",
      "\t\t</div>",
      "\t</div>",
      "<</nobr>>",
      "$0"
    ],
    "description": "Inserts Twine/SugarCube main body layout with video, audio, and menu buttons."
  },
  "Story Passage Layout": {
    "prefix": "storyBody",
    "body": [
      "<<nobr>>",
      "\t<<audio \"${1:audio_id}\" play loop>>",
      "\t<video id=\"bg-video\" autoplay loop muted playsinline>",
      "\t\t<source src=\"sources\\\\Assets\\\\${2:video_name}.mp4\" type=\"video/mp4\">",
      "\t</video>",
      "\t<div class=\"storyContainer\">",
      "\t\t<div class=\"Subtitle\">",
      "\t\t\t<p>Chapter ${3:1} - ${4:Passage Title}</p>",
      "\t\t</div>",
      "\t\t<div class=\"StoryMain\">",
      "\t\t\t<<type 80ms >>",
      "\t\t\t\t<p>${5:Text Here}</p>",
      "\t\t\t<center><button id=\"skip-btn\" class=\"subButton\" onclick=\"skipTypewriter()\">Skip</button></center>",
      "\t\t\t<</type>>",
      "\t\t</div>",
      "\t</div>",
      "\t<div class=\"buttonsParent\">",
      "\t\t<div class=\"button\">",
      "\t\t\t[[${6:Button Text}->${7:Target Passages}]]",
      "\t\t</div>",
      "\t</div>",
      "<</nobr>>",
      "$0"
    ],
    "description": "Inserts Twine/SugarCube layout for a story passage with subtitle, typewriter main text, and choice buttons."
  }
}


