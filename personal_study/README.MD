1.
Severity	Code	Description	Project	File	Line	Suppression State
Error	C4996	'scanf': This function or variable may be unsafe. Consider using scanf_s instead. To disable deprecation, use _CRT_SECURE_NO_WARNINGS. See online help for details.
이라는 오류가 뜬다. scanf자체를 사용하는 것은 unsafe하댄다. 그래서 차라리 scanf_s를 사용하거나, solution에서 아예 바꾸랜다.
[해결방법][https://bymakers.tistory.com/6]