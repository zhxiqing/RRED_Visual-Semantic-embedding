##ImageEmbedding##
###imageEmbedding.h5###
model = Sequential()
model.add(Conv2D(32, (5, 5), padding='same',
                 input_shape=trainImages.shape[1:]))
model.add(Activation('relu'))
model.add(Conv2D(32, (5, 5),padding='same'))
model.add(Activation('relu'))
model.add(MaxPooling2D(pool_size=(2, 2)))
model.add(Dropout(0.25))

model.add(Conv2D(64, (5, 5), padding='same'))
model.add(Activation('relu'))
model.add(Conv2D(64, (3, 3)))
model.add(Activation('relu'))
model.add(MaxPooling2D(pool_size=(2, 2)))
model.add(Dropout(0.25))

model.add(Flatten())
model.add(Dense(128))
model.add(Activation('relu'))
model.add(Dropout(0.5))
model.add(Dense(numClass))
model.add(Activation('softmax'))
###imageEmbedding2.h5###
model = Sequential()
model.add(Conv2D(32, (5, 5), padding='same',
                 input_shape=trainImages.shape[1:]))
model.add(Activation('relu'))
model.add(Conv2D(32, (5, 5),padding='same'))
model.add(Activation('relu'))
model.add(MaxPooling2D(pool_size=(2, 2)))
model.add(Dropout(0.25))

model.add(Conv2D(64, (5, 5), padding='same'))
model.add(Activation('relu'))
model.add(Conv2D(64, (5, 5), padding='same'))
model.add(Activation('relu'))
model.add(Conv2D(64, (3, 3)))
model.add(Activation('relu'))
model.add(MaxPooling2D(pool_size=(2, 2)))
model.add(Dropout(0.25))

model.add(Flatten())
model.add(Dense(128))
model.add(Activation('relu'))
model.add(Dropout(0.5))
model.add(Dense(numClass))
model.add(Activation('softmax'))
Test loss: 3.50066169357
Test accuracy: 0.1875
###imageEmbedding3.h5###
model = Sequential()
model.add(Conv2D(32, (5, 5), padding='same',
                 input_shape=inputSample.shape))
model.add(Activation('relu'))
model.add(Conv2D(32, (5, 5),padding='same'))
model.add(Activation('relu'))
model.add(MaxPooling2D(pool_size=(2, 2)))
model.add(Dropout(0.25))

model.add(Conv2D(64, (5, 5), padding='same'))
model.add(Activation('relu'))
model.add(Conv2D(64, (3, 3)))
model.add(Activation('relu'))
model.add(MaxPooling2D(pool_size=(2, 2)))
model.add(Dropout(0.25))

model.add(Flatten())
model.add(Dense(128))
model.add(Activation('relu'))
model.add(Dropout(0.5))
model.add(Dense(numClass))
model.add(Activation('softmax'))

###imageEmbedding4.h5###
model = Sequential()
model.add(Conv2D(32, (5, 5), padding='same',
                 input_shape=inputSample.shape))
model.add(Activation('relu'))
model.add(Conv2D(32, (5, 5),padding='same'))
model.add(Activation('relu'))
model.add(MaxPooling2D(pool_size=(2, 2)))
model.add(Dropout(0.25))

model.add(Conv2D(64, (5, 5), padding='same'))
model.add(Activation('relu'))
model.add(Conv2D(64, (3, 3)))
model.add(Activation('relu'))
model.add(MaxPooling2D(pool_size=(2, 2)))
model.add(Dropout(0.25))
model.add(Flatten())
model.add(Dense(256))
model.add(Activation('relu'))
model.add(Dropout(0.5))
model.add(Dense(numClass))
model.add(Activation('softmax'))
###imageEmbedding5.h5###
model = Sequential()
model.add(Conv2D(32, (5, 5), padding='same',
                 input_shape=inputSample.shape))
model.add(Activation('relu'))
model.add(Conv2D(32, (5, 5),padding='same'))
model.add(Activation('relu'))
model.add(MaxPooling2D(pool_size=(2, 2)))
model.add(Dropout(0.25))
model.add(Conv2D(64, (5, 5),padding='same'))
model.add(Activation('relu'))
model.add(MaxPooling2D(pool_size=(2, 2)))
model.add(Dropout(0.25))
model.add(Flatten())
model.add(Dense(128))
model.add(Activation('relu'))
model.add(Dropout(0.5))
model.add(Dense(numClass))
model.add(Activation('softmax'))
###imageEmbedding6.h5###
model = Sequential()
model.add(Conv2D(32, (5, 5), padding='same',
                 input_shape=inputSample.shape))
model.add(Activation('relu'))
model.add(Conv2D(32, (5, 5),padding='same'))
model.add(Activation('relu'))
model.add(MaxPooling2D(pool_size=(2, 2)))
model.add(Dropout(0.25))
model.add(Conv2D(64, (5, 5),padding='same'))
model.add(Activation('relu'))
model.add(MaxPooling2D(pool_size=(2, 2)))
model.add(Dropout(0.25))
model.add(Flatten())
model.add(Dense(64))
model.add(Activation('relu'))
model.add(Dropout(0.5))
model.add(Dense(numClass))
model.add(Activation('softmax'))

###imageEmbedding7.h5###
model = Sequential()
model.add(Conv2D(32, (5, 5), padding='same',
                 input_shape=inputSample.shape))
model.add(Activation('relu'))
model.add(Conv2D(32, (5, 5),padding='same'))
model.add(Activation('relu'))
model.add(MaxPooling2D(pool_size=(2, 2)))
model.add(Dropout(0.25))
model.add(Conv2D(64, (5, 5),padding='same'))
model.add(Activation('relu'))
model.add(MaxPooling2D(pool_size=(2, 2)))
model.add(Dropout(0.25))
model.add(Flatten())
model.add(Dense(256))
model.add(Activation('relu'))
model.add(Dropout(0.5))
model.add(Dense(numClass))
model.add(Activation('softmax'))
###imageEmbedding8.h5###
model = Sequential()
model.add(Conv2D(32, (5, 5), padding='same',
                 input_shape=inputSample.shape))
model.add(Activation('relu'))
model.add(Conv2D(32, (5, 5),padding='same'))
model.add(Activation('relu'))
model.add(MaxPooling2D(pool_size=(2, 2)))
model.add(Dropout(0.25))
model.add(Conv2D(64, (5, 5), padding='same'))
model.add(Activation('relu'))
model.add(Conv2D(64, (3, 3)))
model.add(Activation('relu'))
model.add(MaxPooling2D(pool_size=(2, 2)))
model.add(Dropout(0.25))
model.add(Flatten())
model.add(Dense(64))
model.add(Activation('relu'))
model.add(Dropout(0.5))
model.add(Dense(numClass))
model.add(Activation('softmax'))
##TextEmbedding##
###TextEmbeddingL100.h5###
embedding_vecor_length = 32
model = Sequential()
model.add(Embedding(5001, embedding_vecor_length, input_length=max_caption_length, mask_zero=True,name = 'embedding'))
model.add(LSTM(100,name = 'LSTM'))
model.add(Dense(90, activation='softmax',name = 'Dense'))
model.compile(loss='categorical_crossentropy', optimizer='adam', metrics=['accuracy'])

