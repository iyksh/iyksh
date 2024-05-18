<img align="center" src="https://komarev.com/ghpvc/?username=devYaksha"/>++

```C
#include <stdio.h>
#include <stdlib.h>

typedef struct {
    char* contact;
    char* hobbies;
    char* langs;
    char* coding;
} GitHubUser;

int main() {
    GitHubUser* iyksh = malloc(sizeof(GitHubUser)); 

    iyksh->contact = "gssantoz2012@gmail.com";
    iyksh->hobbies = "coding, gaming, reading";
    iyksh->langs = "Portuguese, English, Spanish";
    iyksh->coding = "C/C++, Python, Java, HTML/CSS";

    printf("Metrics:\n");
```
---
<p align="center">
  <img src="/github-metrics.svg" alt="alt text">
</p>


```C

    free(iyksh);

    return 0;
}
