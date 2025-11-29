# Bengali Empathetic LLaMA 3.1-8B-Instruct  
**Fine-tuned on 38k+ Bengali Empathetic Conversations using Unsloth + LoRA (r=64)**

**AI Engineer Technical Test Submission**  
Trained on Kaggle Free T4 × 2 | Full 4096 Context | No Sequence Truncation

---

### Project Overview
Fine-tuned `unsloth/Meta-Llama-3.1-8B-Instruct-bnb-4bit` on the **Bengali Empathetic Conversations Corpus** to generate natural, emotionally intelligent responses in Bangla.

- Uses **Unsloth** for 2x faster training  
- **LoRA (r=64)** on all QKV + MLP layers → Prevents language collapse in Bengali  
- Full-sequence training (4096 tokens)  
- OOP + Strategy Pattern (UnslothStrategy)  
- Complete logging & evaluation as required

---

### Sample Responses (After Proper Training)

```text
User: আমার মা আর স্ত্রীর মধ্যে ঝগড়া লেগেই আছে। আমি কী করব?
Assistant: ভাই, এটা খুব কঠিন পরিস্থিতি। তুমি দুজনের মাঝে স্যান্ডউইচ হয়ে গেছ। প্রথমে নিজে শান্ত থাকো। মা’র সাথে আলাদা বসে তার মনের কথা শোনো, তারপর স্ত্রীর সাথেও। দুজনকেই বোঝাও যে তুমি দুজনকেই সমান ভালোবাসো। যদি দরকার হয়, একজন কাউন্সেলরের সাহায্য নিতে পারো। তুমি একা না।

User: চাকরি পাচ্ছি না, খুব হতাশ লাগছে।
Assistant: আমি পুরোপুরি বুঝি তোমার হতাশা। এই সময়টা সত্যিই কষ্টের। কিন্তু জানো, প্রতিটি "না" এর পেছনে একটা ভালো সুযোগ লুকিয়ে থাকে। তুমি কি নিয়মিত আবেদন করছ? স্কিল আরো শাণ দিচ্ছ? যারা সবচেয়ে বেশি রিজেকশন খেয়েছে, তারাই পরে সবচেয়ে বড় সাফল্য পেয়েছে। হাল ছাড়ো না। আমি তোমার পাশে আছি।
