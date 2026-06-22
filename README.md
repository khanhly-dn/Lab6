# Lab 6 - Computer Vision as IoT Sensor

Repository nay chua bai Lab 6 ve ung dung Computer Vision nhu mot cam bien IoT. Project chinh nam trong thu muc `lab6_cv_as_iot_sensor`.

## Noi dung chinh

- Backend FastAPI xu ly camera/live stream, chup anh, ghi video va phat hien chuyen dong.
- Dashboard HTML de quan sat stream, anh goc, anh da xu ly, metadata va event log.
- Du lieu mau gom anh, video, ket qua xu ly va file CSV log.
- Tai lieu huong dan va checklist nam trong `lab6_cv_as_iot_sensor/docs`.

## Cau truc

```text
lab6_cv_as_iot_sensor/
  app.py
  index.html
  run_lab6_demo.py
  requirements.txt
  data/
  outputs/
  docs/
```

## Chay nhanh

```bash
cd lab6_cv_as_iot_sensor
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
python run_lab6_demo.py
uvicorn app:app --reload --host 0.0.0.0 --port 8000
```

Mo trinh duyet tai:

```text
http://127.0.0.1:8000/
http://127.0.0.1:8000/docs
```

