check_PROGRAMS = newt_test

newt_test_SOURCES = test.c \
                    connection.c \
                    client.c \
                    daemon.c \
                    config.c \
                    newtctl/test_worker.c \
                    unit/test_optparse.c \
                    unit/test_config.c \
                    unit/test_frame.c \
                    unit/test_stomp.c \
                    unit/test_signal.c \
                    unit/test_daemon.c \
                    unit/test_queue.c \
                    unit/test_transaction.c \
                    unit/test_persistent.c \
                    proto/test_connect.c \
                    proto/test_disconnect.c \
                    proto/test_begin.c \
                    proto/test_subscribe.c \
                    proto/test_reply_to.c \
                    proto/test_topic.c \
                    proto/test_error.c
newt_test_LDADD = -lcunit -l_newt -lconfuse -lpthread
newt_test_CFLAGS = -I../src/include/ -I../src/lib
newt_test_LDFLAGS = -L../src/lib/

check:
	./newt_test
