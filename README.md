# Droadrunner

Run a roadrunner app in container.

## Usage

### 1. Create image.

  `docker build -t ${USER}/droadrunner .`

### 2. Run container

  `docker run -dit -p 8080:8080 ${USER}/droadrunner`

### 3. Open browser
  
  `http://localhost:8080`

## Reference

* https://github.com/spiral/roadrunner
