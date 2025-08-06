# 7.2. Runtime fields

Ideally, your data schema is defined at index time. However, there are situations where you may want to define it on the fly. In this lesson, you’ll learn how you can use runtime fields to do so.



# Review
- Use the Painless language.
- Use emit to return a value. The value can be accessed using the doc map. Ex: emit(doc['my_field'].value)
