Q.What is PostgreSQL?
Ans: PostgreSQL হলো একটি শক্তিশালী open source রিলেশনাল ডেটাবেজ ম্যানেজমেন্ট সিস্টেম (RDBMS)। এটি টেবিলের মাধ্যমে ডেটা সংরক্ষণ করে ও সম্পর্ক তৈরি করে। SQL এর মাধ্যমে এটিতে কাজ করা যায় ।

Q. Explain the Primary Key and Foreign Key concepts in PostgreSQL.
Ans: Primary Key হলো এমন একটি key যা একটি টেবিলের প্রতিটি row কে অন্যদের থেকে আলাদা করে চিনতে সাহায্য করে। এটি অবশ্যই ইউনিক হবে এবং Null হতে পারবে না। একটি টেবিলে একটিই primary key থাকে। এটি একাধিক কলাম নিয়েও তৈরি হতে পারে

Q.Explain the purpose of the WHERE clause in a SELECT statement.
Ans: WHERE ব্যবহার করা হয় শর্ত অনুযায়ী ডেটা ফিল্টার করার জন্য। এটি শুধু সেই row কেই দেয় যেগুলো একটি নির্দিষ্ট শর্ত পূরণ করে। where দিয়ে আরো অনেক কাজ করা যায়।

Q.What are the LIMIT and OFFSET clauses used for?
Ans: LIMIT ব্যবহার করা হয় output সংখ্যা নির্দিষ্ট করতে, অর্থাৎ কতটি row আমরা দেখতে চাই সেটি নির্দিষ্ট করার জন্য।
OFFSET ব্যবহার করা হয় output শুরু থেকে কতটি রেকর্ড বাদ দিতে হবে, তা নির্ধারণ করতে। limit এবং offset pagination এ কাজ করা যায়।

Q.How can you modify data using UPDATE statements?
Ans: UPDATE স্টেটমেন্ট ব্যবহার করে একটি টেবিলে থাকা ডেটা পরিবর্তন করা যায়। এটি টেবিলের এক বা একাধিক row তে থাকা মান পরিবর্তনের জন্য ব্যবহৃত হয়।
যেমন: UPDATE table_name
SET column1 = new_value1,
column2 = new_value2
WHERE condition;
