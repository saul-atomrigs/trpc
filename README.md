# tRPC
- 일반 함수를 호출하여 백엔드의 API를 호출할 수 있음. 프론트엔드(API 호출)와 백엔드(endpoint 함수) 타입 공유.  
- JSON-RPC사양과 HTTP 전송 계층 사용
- react-query 결합하여 캐칭 지원. 내부적으로 react-quer의 `useQuery`, `useMutation`을 사용.
