# pm

> একটি Android ডিভাইসে অ্যাপ্লিকেশন সম্পর্কে তথ্য দেখান।
> আরও তথ্য পাবেন: <https://developer.android.com/studio/command-line/adb#pm>.

- সমস্ত ইনস্টল করা অ্যাপের একটি তালিকা প্রিন্ট করুন:

`pm list packages`

- সমস্ত ইনস্টল করা সিস্টেম অ্যাপের একটি তালিকা প্রিন্ট করুন:

`pm list packages -s`

- সমস্ত ইনস্টল করা থার্ড-পার্টি অ্যাপের একটি তালিকা প্রিন্ট করুন:

`pm list packages -3`

- নির্দিষ্ট কীওয়ার্ডের সাথে মিলে যাওয়া অ্যাপগুলির একটি তালিকা প্রিন্ট করুন:

`pm list packages {{কীওয়ার্ড১ কীওয়ার্ড২...}}`

- একটি নির্দিষ্ট অ্যাপের APK এর পথ প্রিন্ট করুন:

`pm path {{অ্যাপ}}`