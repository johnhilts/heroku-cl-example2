web: ASDF_OUTPUT_TRANSLATIONS=/: ./sbcl/sbcl-2.1.1-x86-64-linux/run-sbcl.sh --load quicklisp/setup.lisp --eval "(ql:quickload :hunchentoot)" --eval "(hunchentoot:start (make-instance 'hunchentoot:easy-acceptor :port $PORT))" --eval "(loop (sleep 1000))"
