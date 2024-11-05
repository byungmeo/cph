# Competitive Programming Helper (cph) + C#
C# 호환 가능

오직 Test Case Judge 기능 호환에만 중점을 두고 수정 함.

dotnet run --project {프로젝트폴더} 로 테스트 케이스가 실행되기 때문에 문제점이 많음.
1. 여러 개의 테스트 케이스 실행 시 매번 빌드가 되는 단점 있음.
2. 문제 불러오기 자체는 잘 작동하나 한 프로젝트에 2개 이상의 cs파일이 존재할 경우 생기는 문제는 알아서 해결하여야 함.
3. ONLINE_JUDGE 또는 커스텀 Args, Command같은 설정은 반영되지 않음.

## License

Copyright (C) 2019 - Present Divyanshu Agrawal

This program is free software: you can redistribute it and/or modify it under
the terms of the GNU General Public License as published by the Free Software
Foundation, either version 3 of the License, or (at your option) any later
version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with
this program. If not, see https://www.gnu.org/licenses/.
