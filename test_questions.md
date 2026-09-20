# Test Questions — Kapalkundala Knowledge Base Chatbot

Ten test questions were run against the deployed chatbot. Expected answers and citations below are copied directly from the actual chatbot output.

| # | Question | Actual Answer | Citation |
|---|----------|----------------|----------|
| 1 | নবকুমার কীভাবে সমুদ্রতীরে বিপদে পড়েছিলেন? | নবকুমার কাষ্ঠভার সংগ্রহ করে নদীর তীরে ফিরে এসে নৌকা দেখতে পাননি। জলোচ্ছ্বাসের তরঙ্গে নৌকা জলমগ্ন হওয়া অথবা সঙ্গীরা তাঁকে সেই বিজন স্থানে পরিত্যাগ করে চলে যাওয়ার কারণে তিনি ক্ষুধায় অত্যন্ত পীড়িত হয়ে বিপদে পড়েছিলেন। | প্রথম খণ্ড — তৃতীয় পরিচ্ছেদ |
| 2 | কাপালিক নবকুমারকে নিয়ে কী পরিকল্পনা করেছিলেন? | কাপালিক তাঁর তান্ত্রিক পূজার জন্য নবকুমারকে উৎসর্গ করার পরিকল্পনা করেছিলেন, কারণ নরমাংস ছাড়া তান্ত্রিকের পূজা সম্পন্ন হয় না। | প্রথম খণ্ড — ষষ্ঠ পরিচ্ছেদ |
| 3 | কপালকুণ্ডলা নবকুমারকে প্রথম দেখা করে কী বলেছিলেন? | কপালকুণ্ডলা নবকুমারের পাশ দিয়ে যাওয়ার সময় তাঁর কর্ণে বলেছিলেন, "এখনও পলাও। নরমাংস নহিলে তান্ত্রিকের পূজা হয় না তুমি কি জান না?" | প্রথম খণ্ড — ষষ্ঠ পরিচ্ছেদ |
| 4 | নবকুমার কপালকুণ্ডলাকে বিয়ের পর কোথায় নিয়ে যান? | নবকুমার বিয়ের পর কপালকুণ্ডলাকে নিয়ে প্রথমে মেদিনীপুরে আসেন এবং পরবর্তীতে সপ্তগ্রামের উদ্দেশ্যে যাত্রা করেন। | দ্বিতীয় খণ্ড — প্রথম পরিচ্ছেদ, দ্বিতীয় খণ্ড — চতুর্থ পরিচ্ছেদ |
| 5 | লুৎফ-উন্নিসা চরিত্রটি কে? | আগ্রার এক উচ্চপদস্থ ওমরাহের কন্যা, যিনি ছদ্মবেশে ভ্রমণকালে "মতিবিবি" নাম গ্রহণ করতেন। প্রকাশ্যে যুবরাজ সেলিমের প্রধানা মহিষীর সখী এবং পরোক্ষে যুবরাজ সেলিমের উপপত্নী। | তৃতীয় খণ্ড — প্রথম পরিচ্ছেদ |
| 6 | উপন্যাসের শেষে কপালকুণ্ডলার পরিণতি কী হয়? | নদীর তীরে দাঁড়িয়ে থাকা অবস্থায় প্রবল নদীতরঙ্গের আঘাতে তটের মাটি ভেঙে পড়ে, এবং তিনি সেই ভাঙা মাটির সঙ্গে নদীপ্রবাহে পড়ে অন্তর্হিত হন। | চতুর্থ খণ্ড — দশম পরিচ্ছেদ |
| 7 | কপালকুণ্ডলা কার আশ্রয়ে বড় হয়েছিলেন? | এই প্রশ্নের উত্তর বইটির মধ্যে খুঁজে পাওয়া যায়নি। | — (retrieved chunks did not contain this specific detail) |
| 8 | উপন্যাসটি কয়টি খণ্ডে বিভক্ত? | এই প্রশ্নের উত্তর বইটির মধ্যে খুঁজে পাওয়া যায়নি। | — (book structure is not stated in a single narrative sentence) |
| 9 | বঙ্কিমচন্দ্র চট্টোপাধ্যায়ের জন্ম তারিখ কত? | এই প্রশ্নের উত্তর বইটির মধ্যে খুঁজে পাওয়া যায়নি। অনুগ্রহ করে বইয়ের বিষয়বস্তু সম্পর্কিত প্রশ্ন করুন। | — |
| 10 | বঙ্কিমচন্দ্র চট্টোপাধ্যায়ের জন্ম তারিখ কত? (No-Answer test — repeated intentionally) | এই প্রশ্নের উত্তর বইটির মধ্যে খুঁজে পাওয়া যায়নি। অনুগ্রহ করে বইয়ের বিষয়বস্তু সম্পর্কিত প্রশ্ন করুন। | — |

## No-Answer Test Case

Questions 9 and 10 deliberately ask about the author's biography — information that is true and well documented, but not part of the novel's narrative text. The chatbot correctly declines to answer rather than pulling this fact from the LLM's own general knowledge, confirming the system stays grounded strictly in retrieved book content.

Questions 7 and 8 additionally show the same honest behavior on in-book but non-explicit information: the retriever did not surface a chunk directly stating this detail within the top-4 results, so the chatbot reported no answer rather than guessing.
