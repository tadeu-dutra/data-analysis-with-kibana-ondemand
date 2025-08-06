# 7.2. Runtime fields

Ideally, your data schema is defined at index time. However, there are situations where you may want to define it on the fly. In this lesson, you’ll learn how you can use runtime fields to do so.


In this lab, you will create, query, and visualize a runtime field.

<img width="1919" height="975" alt="image" src="https://github.com/user-attachments/assets/b4ec72eb-5abc-4050-aaae-0d7837f0a351" />

<img width="556" height="533" alt="image" src="https://github.com/user-attachments/assets/b0596311-9ace-4158-99c8-562b1f4cfa6f" />

# Summary:

In this lab, you created, queried, and visualized a runtime field.



# Review
- Use the Painless language.
- Use emit to return a value. The value can be accessed using the doc map. Ex: emit(doc['my_field'].value)
- Although runtime fields can be quite useful in certain instances, you should use them with caution, because they can be computationally expensive.
