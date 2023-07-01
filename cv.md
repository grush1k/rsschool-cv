![](/rsschool-cv/img/ava.jpg)
# Valentin Grushevskiy
***
## My Contact Info
- **Adress:** Nakonechnikova street, Baranovichi, Belarus
- **Phone:** +375298319010
- **E-mail:** huawei_p8_lite_2017@mail.ru
- **GitHub:** [grush1k](https://github.com/grush1k)
- **Telegram:** [grush1k](https://t.me/grush1k)
- **Discord:** [grush1k](https://discord.com/channels/@me)
***
## Summary
>Currently, my priority is comprehensive education, the main purpose of which is to gain extensive experience in the field of IT. My strengths are sociability, stress tolerance, and a responsible approach to performing the tasks I need.
***
## Skills
- HTML
- CSS(Preprocessor SCSS)
- C++(basic knowledge)
- Photoshop
- AutoCad
- WordPress
- Figma(for web development)
***
## Code examples
```C++
void ShellSort(int n, timetable* mass)
{
    int i, j, step;
    timetable tmp;
    for (step = n / 2; step > 0; step /= 2)
        for (i = step; i < n; i++)
        {
            tmp = mass[i];
            for (j = i; j >= step; j -= step)
            {
                if (tmp.number < mass[j - step].number)
                    mass[j] = mass[j - step];
                else
                    break;
            }
            mass[j] = tmp;
        }
}
void Search_Binary(timetable arr[], int left, int right, int key)
{
    int midd;
    while (1)
    {
        midd = (left + right) / 2;

        if (key < arr[midd].number)
            right = midd - 1;
        else if (key > arr[midd].number)
            left = midd + 1;
        else
        {
            cout << "Race number: " << arr[midd].number << "\n"<< "Town: " << arr[midd].town << endl;
            break;
        }

        if (left > right)
        {
            cout << "Mistake" << endl;
            break;
        }

    }
}
```
***
## Education
- **Gymnasium №4 Baranovichi**, *General education(secondary education)*
    - Physico-mathematical, computer cientist
- **BSUIR**(graduated from the 1st year)
    - Faculty of Information Technology and Management
    - Specialization: Automated information processing systems
***