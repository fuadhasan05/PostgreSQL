**1. What is PostgreSQL?**
PostgreSQL হলো একটি শক্তিশালী এবং উন্নত ডেটাবেস সিস্টেম যা ডেভেলপার এবং সংস্থাগুলোর মধ্যে ব্যাপক জনপ্রিয়, বিশেষ করে যারা performance ও reliability চাই। 

**2. What is the purpose of a database schema in PostgreSQL?**
Schema হচ্ছে PostgreSQL-এ অবজেক্ট সংগঠনের একটি উপায়, যা ডেটাবেসকে পরিপাটি, নিরাপদ এবং সহজে ব্যবস্থাপনাযোগ্য করে তোলে।

**3. Explain the Primary Key and Foreign Key concepts in PostgreSQL.**
Primary Key হল এক বা একাধিক কলামের সমন্বয়, যা প্রতিটি রেকর্ডকে (unique) এবং (NOT NULL) এ রাখে। এটি প্রতিটি টেবিলের জন্য রেকর্ডগুলোকে আলাদা করে চিহ্নিত করে।

Foreign Key একটি টেবিলকে আরেকটি টেবিলের সাথে সংযুক্ত (relate) করে। এটি এক টেবিলের কলামের মাধ্যমে অন্য টেবিলের Primary Key বা Unique Key-কে রেফারেন্স (reference) করে।

**4. What is the difference between the VARCHAR and CHAR data types?**
VARCHAR ব্যবহার করা হয় যখন স্ট্রিংয়ের দৈর্ঘ্য বিভিন্ন হতে পারে।
CHAR ব্যবহার করা হয় যখন স্ট্রিংয়ের দৈর্ঘ্য একই হবে এবং নির্দিষ্ট।

**5. Explain the purpose of the WHERE clause in a SELECT statement.**
WHERE ক্লজ হলো একটি (condition) যা SELECT স্টেটমেন্ট–এ ব্যবহার করে ডেটাবেস থেকে নির্দিষ্ট তথ্য বের করে।
