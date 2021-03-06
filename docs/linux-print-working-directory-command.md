# 현재 작업 위치 얻기

?> 링크: [https://linuxsurvival.com/linux-print-working-directory-command/](https://linuxsurvival.com/linux-print-working-directory-command/)

일부 개발자들은 디렉터리를 변경할 때마다 프롬프트에 변경 내용이 표시되도록 리눅스 설정을 변경해 놓고 작업합니다. 설정을 변경하면 오른쪽 프롬프트처럼 머신의 이름(zoo)이 나오고, 콜론(:) 옆에 현재 작업 디렉터리의 이름(primates)이 보입니다. 이렇게 설정을 변경해 놓지 않았다면 현재 작업 디렉터리가 어디인지 알려주는 명령어를 입력해 직접 확인해야 합니다.

‘print working directory’의 약자인 `pwd` 명령어를 입력하면 현재 작업 디렉터리를 알 수 있습니다.

명령 프롬프트에 `pwd`를 입력해 현재 작업 디렉터리를 확인해 봅시다. 그리고 난 후 두 번째 명령어로 현재 디렉터리에 있는 내용을 출력해주는 명령어를 입력해 제대로 파일을 옮겼는지 확인해봅시다.

> `명령어입력`

- 다이얼로그 창

```다이얼로그 창
맞았습니다.
```

```다이얼로그 창
‘/animals/primates’는 파일 구조를 나타내는 트리에서 현재 어디서 작업하고 있는지를 나타내줍니다. 이를 ‘파일 경로’라고 부르는데 파일 경로에 대한 자세한 내용은 뒤쪽에서 다루겠습니다. Linux survival에선 간결성을 위해 많은 것들을 생략하였습니다. 실제 리눅스 환경에서는 파일 트리가 훨씬 더 복잡하고 animals의 위치 또한 트리 한참 아래에 있을 확률이 높습니다.
```

> `명령어입력`

- 다이얼로그 창

```다이얼로그 창
맞았습니다.
```

<br>
<br>

?> 링크: [https://linuxsurvival.com/linux-print-working-directory-command/](https://linuxsurvival.com/linux-print-working-directory-command/)

`ls` 명령어로 파일을 제대로 옮겼는지 확인했으니, 다시 한 단계 위 디렉터리인 animals로 돌아가 정리를 다시 시작해봅시다.

이전 디렉터리(‘부모’ 디렉터리)로 돌아가려면 `cd` 명령어 옆에 특별한 ‘인수(argument)’를 붙여줘야 합니다.

> cd ..

앞으로 `..`을 보면 현재 디렉터리의 상위 디렉터리를 나타낸다고 생각하시면 됩니다(옮긴이 - `cd ../..`, `cd ../../..`도 사용 가능합니다).

인수는 컴퓨터 용어로, 커맨드가 직접 실행되는 ‘무언가'를 나타냅니다. `cd ..`에선 명령어 cd 옆에 붙은 ..가 인수입니다. 그리고 ‘무언가'는 디렉터리 입니다.

지금까지 입력했던 명령어들 다수에서 인수를 써왔습니다. `more cobras` 명령어에서 cobras는 more의 인수입니다. 이 경우 ‘무언가'는 파일입니다.

명령어와 인수 사이에는 빈칸을 하나 넣어줘야 한다는 점을 잊지 마시기 바랍니다. Windows의 커맨드 프롬프트에선 이런 제약이 없어서 Windows 사용자는 이런 제약이 불편할 수 있습니다. Windows에선 `cd..`
를 입력해도 에러가 발생하지 않지만, 리눅스에선 에러 메시지가 뜨기 때문입니다.

<br>
<br>

?> 링크: [https://linuxsurvival.com/linux-change-to-parent-directory-part-2/
](https://linuxsurvival.com/linux-change-to-parent-directory-part-2/)

상위 디렉터리로 이동하는 명령어를 입력해 animals 디렉터리로 이동한 후, 현재 작업 디렉터리를 출력해주는 명령어를 입력해 원하는 디렉터리로 변경되었는지 확인해 봅시다.

> `명령어입력`

- 다이얼로그 창

```다이얼로그 창
맞았습니다.
```

```다이얼로그 창
OK 버튼을 누르면 프롬프트로 다시 돌아갑니다. 프롬프트에서 현재 작업 디렉터리를 나타내는 명령어를 입력해 봅시다.
```

> `명령어입력`

```다이얼로그 창
맞았습니다.
```

<br>
<br>

?> 링크: [https://linuxsurvival.com/linux-mkdir-and-mv-commands/](https://linuxsurvival.com/linux-mkdir-and-mv-commands/)

벌써 꽤 많은 작업을 했습니다. 이제 cobras 파일이 들어갈 장소가 필요하다는 생각이 들 겁니다. cobras를 reptiles(파충류)에 넣어봅시다.

두 단계를 거쳐야 원하는 작업을 할 수 있습니다.

  1)‘reptiles’라는 이름을 가진 디렉터리 만들기
  2) cobras 파일을 reptiles 디렉터리에 옮기기

각 단계에 해당하는 명령어를 입력해 원하는 작업을 해봅시다. 이 과정이 끝나면 지금까지 배운 것들을 복습해볼 수 있는 퀴즈를 풀어보겠습니다.

> `명령어입력`

```다이얼로그 창
맞았습니다.
```

> `명령어입력`

```다이얼로그 창
맞았습니다.
```


